The aim of this project was to implement effective energy-saving strategies to reduce energy consumption, CO2 emissions and execution time. The project analyzed five datasets containing data derived from electronic health records. The chosen method was Random Forest model with a repeated hold-out validation of 100 iterations and the performance was measured through the Matthews correlation coefficient (MCC). For each dataset two main approaches were developed:

* a Standard code, characterized by a higher number of trees and unlimited maximum depth of the trees
* a Green code which aimed to reduce energy consumption, CO2 emissions and execution time by modifying the values of the hyperparameters
An additional strategy based on feature selection ranked by importance was evaluated on the first dataset but it was later discarded due to its worse performance compared to the model with only the strategy based on the adjustment of hyperparameters.

The repository contains the following files: the Python notebook, the R Markdown file and the final report in PDF.
In Python the level of carbon emissions were measured through the CodeCarbon library while in R it was used the reticulate package.

To reproduce the experiments it is recommended to follow the steps of the report while executing the corresponding code firstly in Python and then in R.
