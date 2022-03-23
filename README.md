# model_diagnostics

This repository contains a model diagnostic notebook.<br />
Through it, an analysis of the performance of an individual model can be visualized.<br />
Please make sure you meet the following requirements before using this notebook - <br />
<br />
1.	<b>Label column –</b> <br />
  •	A column describing the label for each sample. <br />
  •	Examples - train, val, test normal, test abnormal, test active, etc.<br />
<br />
2.	<b>Constants –</b><br />
  •	Please fill out the second cell with the relevant columns names.<br />
  •	The list of meta-features will be based on the METAFEATURES constant variable. The test looks for columns containing a substring of at least one element from the
    METAFEATURES list.<br />
  •	As long as there are no residual or residual absolute columns, please use the default names (as shown in the example notebook). These columns will be added to the
    dataframe.<br />
