<p><span style="color:#212121"><span style="background-color:#ffffff">Handling missing values is an essential part of the data cleaning and preparation process because almost all data in real life comes with some missing values.</span></span></p>

<p><span style="color:#212121"><span style="background-color:#ffffff">Pandas provides </span></span><span style="color:#212121"><span style="background-color:#ffffff">isnull()</span></span><span style="color:#212121"><span style="background-color:#ffffff">, </span></span><span style="color:#212121"><span style="background-color:#ffffff">isna()</span></span><span style="color:#212121"><span style="background-color:#ffffff"> functions to detect missing values. Both of them do the same thing.</span></span></p>

<ul>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">df.isna()</span></span><span style="color:#212121"><span style="background-color:#ffffff"> returns the dataframe with boolean values indicating missing values.</span></span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">You can also choose to use </span></span><span style="color:#212121"><span style="background-color:#ffffff">notna()</span></span><span style="color:#212121"><span style="background-color:#ffffff"> which is just the opposite of isna().</span></span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">df.isna().any()</span></span><span style="color:#212121"><span style="background-color:#ffffff"> returns a boolean value for each column. If there is at least one missing value in that column, the result is True.</span></span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">df.isna().sum()</span></span><span style="color:#212121"><span style="background-color:#ffffff"> returns the number of missing values in each column.</span></span></li>
</ul>

<p>&nbsp;</p>

<h2><span style="color:#212121">1.&nbsp;</span><span style="color:#212121"><span style="background-color:#ffffff">isna()</span></span></h2>

<p style="text-align:center"><img alt="" height="453" src="https://dphi-courses.s3.ap-south-1.amazonaws.com/introduction-to-eda/Module2/ss10.png" width="549" /></p>

<h3><span style="color:#212121"><strong>Observation:</strong></span></h3>

<p><span style="color:#212121">There is no missing value in any column</span></p>

<h2>2.&nbsp;<span style="color:#212121"><span style="background-color:#ffffff">info()</span></span></h2>

<p><span style="color:#212121"><span style="background-color:#ffffff">df.info returns information about the data frame including the data types of each column, number of null values in each column and memory usage of the entire data.</span></span></p>

<p style="text-align:center"><img alt="" height="511" src="https://dphi-courses.s3.ap-south-1.amazonaws.com/introduction-to-eda/Module2/ss11.png" width="629" /></p>

<h3><span style="color:#212121"><span style="background-color:#ffffff"><strong>Observations:</strong></span></span></h3>

<ul>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">The data has only float and integer values.</span></span></li>
	<li style="list-style-type:disc"><span style="color:#212121"><span style="background-color:#ffffff">There are no missing values</span></span></li>
</ul>