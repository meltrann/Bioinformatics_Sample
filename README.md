# Bioinformatics_Sample

This repository contains sample work demonstrating data processing and visualization tasks for Bioinformatics data. The provided files are as follows:

* MUX4111-WHH1754.wgs_metrics.txt: This file contains an example output from picard CollectWgsMetrics and will be used for parsing.
* sample_metadata.csv: This CSV file contains a list of samples along with their associated metadata.
* sample_metrics.csv: This CSV file contains parsed picard outputs for the samples, including information on library ID, PCT_1X, and MEAN_COVERAGE.

#### Task 1: Data Parsing
* The first task involves parsing the MUX4111-WHH1754.wgs_metrics.txt file to extract specific information. The data to be extracted includes the Library ID, PCT_1X, and MEAN_COVERAGE.

#### Task 2: Data Processing
* In the second task, we will combine the data from sample_metadata.csv and sample_metrics.csv to create a unified dataset. This dataset will serve as the basis for subsequent data visualization.

#### Task 3: Data Visualization
* The third task focuses on visualizing the PCT_1X metric in a way that effectively represents the data. I used the newly created dataset to plot the PCT_1X metric grouped by mux_id to gain insights into the data distribution.

#### Task 4: Interpretation
* The interpretation will involve understanding the significance of the PCT_1X metric, its variations across different mux_ids, and how it relates to the experiment's objectives.

Throughout this project, the code will be provided in a Juypter Notebook and organized into relevant directories for each task. 

Please feel free to explore the code and data provided to gain insights into the data processing and visualization techniques I used in this sample work. If you have any questions or feedback, don't hesitate to contact me. Happy exploring!
