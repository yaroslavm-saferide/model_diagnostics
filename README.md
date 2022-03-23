<p><img alt="" src="https://media-exp1.licdn.com/dms/image/C560BAQHrp_WoJMMFlw/company-logo_200_200/0/1639492632722?e=2147483647&amp;v=beta&amp;t=14tiwPWRBc2nMTG9jVUh1c3Xg1izHEGwIyVvuj41Ot8" style="height:200px; width:200px" /></p>

<p>This repository contains a model diagnostic notebook.<br />
Through it, an analysis of the performance of an individual model can be visualized.<br />
<u><strong>Please make sure you meet the following requirements before using this notebook -</strong></u><br />
&nbsp;</p>

<ol>
	<li><strong>Label column &ndash;</strong></li>
</ol>

<ul>
	<li>A column describing the label for each sample.</li>
	<li>Examples - train, val, test normal, test abnormal, test active, etc.</li>
</ul>

<p>&nbsp;</p>

<ol start="2">
	<li><strong>Constants &ndash;</strong></li>
</ol>

<ul>
	<li>Please fill out the second cell with the names of the relevant columns.</li>
	<li>The list of meta-features will be based on the METAFEATURES constant variable. The test looks for columns containing a substring of at least one element from the METAFEATURES list.</li>
	<li>As long as there are no residual or residual absolute columns, please use the default names (as shown in the example notebook). These columns will be added to the dataframe.</li>
</ul>
