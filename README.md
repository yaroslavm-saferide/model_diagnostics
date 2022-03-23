# model_diagnostics

This repository contains a model diagnostic notebook.
Through it, an analysis of the performance of an individual model can be visualized.
Please make sure you meet the following requirements before using this notebook - 

1.	Label column – \n
  •	A column describing the label for each sample. \n
  •	Examples - train, val, test normal, test abnormal, test active, etc.\n
\n
2.	Constants - \n
  •	Please fill out the second cell with the relevant columns names.\n
  •	The list of meta-features will be based on the METAFEATURES constant variable. The test looks for columns containing a substring of at least one element from the
    METAFEATURES list.\n
  •	As long as there are no residual or residual absolute columns, please use the default names (as shown in the example notebook). These columns will be added to the
    dataframe.\n
