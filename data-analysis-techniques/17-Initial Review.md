<p>&nbsp;&nbsp;</p>

<h2>1. Head</h2>

<p><span style="color:#212121">To take a closer look at the data, we take the help of &ldquo; .head()&rdquo; function of pandas library which returns the first five observations of the data set. Similarly, &ldquo;.tail()&rdquo; returns last five observations of the data set.</span></p>

<p><span style="color:#212121">You&rsquo;ll see that this is a great way to get an initial feeling of your data and maybe understand it a bit better already!</span></p>

<p style="text-align:center"><img alt="" height="488" src="https://dphi-courses.s3.ap-south-1.amazonaws.com/introduction-to-eda/Module2/ss3.png" width="1561" /></p>

<p>&nbsp;</p>

<p>&nbsp;</p>

<h2>2. Shape</h2>

<p><span style="color:#212121">Find out the total number of rows and columns in the dataset using &ldquo;.shape&rdquo;.</span></p>

<p style="text-align:center"><img alt="" height="89" src="https://dphi-courses.s3.ap-south-1.amazonaws.com/introduction-to-eda/Module2/ss4.png" width="213" /></p>

<h3><span style="color:#212121"><strong>Observations:</strong></span></h3>

<ul>
	<li style="list-style-type:disc"><span style="color:#212121">Dataset comprises 1599 observations(rows) and 12 features(columns).</span></li>
	<li style="list-style-type:disc"><span style="color:#212121">Out of the 12, one is the target variable and rest 11 are input&nbsp;variables.</span></li>
</ul>

<p>&nbsp;</p>

<h2><span style="color:#212121">3.&nbsp;&nbsp;Get a Statistical Overview using Describe</span></h2>

<p><span style="color:#212121">The describe() function in pandas is very handy in getting various summary statistics. This function returns the count, mean, standard deviation, minimum and maximum values and the quantiles of the data.</span></p>

<hr />
<p><span style="color:#212121">REFRESHER: Outliers are observations that are significantly different from other data points.</span></p>

<hr />
<p><span style="color:#212121">It is always interesting to know the basic statistical characteristics of each numerical variable.</span></p>

<p style="text-align:center"><img alt="" height="425" src="https://dphi-courses.s3.ap-south-1.amazonaws.com/introduction-to-eda/Module2/ss5.png" width="1779" /></p>

<p>&nbsp;</p>

<p><span style="color:#212121">Let&#39;s explore different statistical measures that we have got from describe().</span></p>

<ul>
	<li style="list-style-type:disc"><span style="color:#212121"><strong>count:</strong></span><span style="color:#212121"> total count of non-null values in the column</span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><strong>mean</strong></span><span style="color:#212121">: the average of all the values in that column</span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><strong>min:</strong></span><span style="color:#212121"> the minimum value in the column</span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><strong>max:</strong></span><span style="color:#212121"> the maximum value in the column</span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><strong>25%:</strong></span><span style="color:#212121"> first quartile in the column after we arrange those values in ascending order</span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><strong>50%:</strong></span><span style="color:#212121"> this is the median or the second quartile</span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><strong>75%:</strong></span><span style="color:#212121"> the third quartile</span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><strong>std:</strong></span><span style="color:#212121"> this is the standard deviation (i.e. measure of depreciation, you must have read in the basics of statistics study material)</span></li>
</ul>

<p><span style="color:#212121"><strong>Note:</strong></span><span style="color:#212121"> 25%, 50%, and 75% are nothing but corresponding percentile values</span></p>

<p>&nbsp;</p>

<h3><span style="color:#212121"><strong>Observations:</strong></span></h3>

<ul>
	<li style="list-style-type:disc"><span style="color:#212121">Here as you can notice the median value is less than the mean value of each column (except for quality). Median is represented by 50%(50th percentile) in the index column.</span>This signifies the presence of Outliers. For example, a data set includes values: 30, 31, 32, and 2. The mean value (23.75), which is lower than the median of the data (30.5), is greatly affected by the extreme data point(2).&nbsp;</li>
	<li style="list-style-type:disc"><span style="color:#212121">There is notably a large difference between 75th %tile and max values of predictors &ldquo;residual sugar&rdquo;, &rdquo; free sulfur dioxide&rdquo;, &rdquo; total sulfur dioxide&rdquo;.&nbsp;</span><span style="color:#212121">This indicates that some values of these 3 variables lie much farther from the general range of values( up to 75th %tile)&nbsp;</span></li>
	<li style="list-style-type:disc"><span style="color:#212121">Thus, the observations 1 and 2 suggest that there are extreme values i.e Outliers in our dataset.&nbsp;</span></li>
</ul>