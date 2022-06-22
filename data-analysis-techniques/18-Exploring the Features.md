# Exploring the Features/Variables

<p><span style="color:#212121">Variables and features both are the same, they are often used interchangeably. All the column names in a dataset are variables.</span></p>

<p><span style="color:#212121">Let&#39;s explore the features/columns of the datasets.</span></p>

<p style="text-align:center"><img alt="" height="149" src="https://dphi-courses.s3.ap-south-1.amazonaws.com/introduction-to-eda/Module2/ss6.png" width="758" /></p>

<p>&nbsp;</p>

<p>&nbsp;</p>

<h4><span style="color:#212121"><strong>Target Variable:</strong></span></h4>

<p><span style="color:#212121">The target variable of a dataset is the feature of a dataset about which you want to gain a deeper understanding. It is the variable that is, or should be the output.</span></p>

<p><span style="color:#212121">Here </span><span style="color:#212121"><strong>quality</strong></span><span style="color:#212121"> is the target variable as we&#39;re trying to know which of the two types of wines have better quality.</span></p>

<p>&nbsp;</p>

<h4><span style="color:#212121"><strong>Input Variables:</strong></span></h4>

<p><span style="color:#212121">One or more variables that are used to determine (or predict) the &#39;Target Variable&#39; are known as Input Variables. They are sometimes called Predictor Variable as well.</span></p>

<p><span style="color:#212121">In our example, the input variables are: &#39;fixed acidity&#39;, &#39;volatile acidity&#39;, &#39;citric acid&#39;, &#39;residual sugar&#39;, &#39;chlorides&#39;, &#39;free sulfur dioxide&#39;, &#39;total sulfur dioxide&#39;, &#39;density&#39;,&#39;pH&#39;, &#39;sulphates&#39;, and &#39;alcohol&#39;.</span></p>

<p><span style="color:#212121">All of these will help us predict the quality of the wine.</span></p>

<p>&nbsp;</p>

<p><span style="color:#212121"><span style="background-color:#ffffff">After loading the data, it is important to examine the data. It is usually not recommended to directly throw all the data into the model without understanding the data. This step always helps in improving our model.</span></span></p>

<p>&nbsp;</p>

<h2><span style="color:#212121"><span style="background-color:#ffffff">1.&nbsp;Unique Values of Quality(Target Variable)</span></span></h2>

<p style="text-align:center"><img alt="" height="271" src="https://dphi-courses.s3.ap-south-1.amazonaws.com/introduction-to-eda/Module2/ss7.png" width="499" /></p>

<p>&nbsp;</p>

<h3><span style="color:#212121"><span style="background-color:#ffffff"><strong>Observations:</strong></span></span></h3>

<p><span style="color:#212121"><span style="background-color:#ffffff">Few key insights just by looking at the target variable are as follows:</span></span></p>

<ul>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">Target variable/Dependent variable is discrete and categorical in nature.</span></span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">&ldquo;quality&rdquo; score scale ranges from 1 to 10; 1 being poor and 10 being the best.</span></span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">1,2,9 &amp; 10 Quality ratings are not given by any observation. Only scores obtained are between 3 to 8.</span></span></li>
</ul>

<p>&nbsp;</p>

<h2><span style="color:#212121"><span style="background-color:#ffffff">2.&nbsp;Frequency Counts of each Quality Value</span></span></h2>

<p style="text-align:center"><img alt="" height="338" src="https://dphi-courses.s3.ap-south-1.amazonaws.com/introduction-to-eda/Module2/ss8.png" width="556" /></p>

<h3><span style="color:#212121"><span style="background-color:#ffffff"><strong>Observations:</strong></span></span></h3>

<ul>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">This tells us the vote count of each quality score in descending order.</span></span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">&ldquo;quality&rdquo; has most values concentrated in the categories 5, 6 and 7.</span></span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">Only a few observations made for the categories 3 &amp; 8.</span></span></li>
</ul>

<p>&nbsp;</p>

<h2><span style="color:#212121"><span style="background-color:#ffffff">3.&nbsp;Renaming Columns</span></span></h2>

<p><span style="color:#212121"><span style="background-color:#ffffff">Let&#39;s rename the columns which contain spaces in their names and replace the spaces with underscores.</span></span></p>

<p style="text-align:center"><img alt="" height="447" src="https://dphi-courses.s3.ap-south-1.amazonaws.com/introduction-to-eda/Module2/ss9.png" width="1318" /></p>

<p>&nbsp;</p>