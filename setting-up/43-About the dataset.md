<p><span style="color:#212121">The dataset we will be using here is the </span><a href="https://archive.ics.uci.edu/ml/datasets/wine+quality" style="text-decoration:none"><span style="color:#1155cc"><u>Wine Quality data</u></span></a><span style="color:#212121"> containing certain information about red and white wine.</span></p>

<p><span style="color:#212121">Quality of the wine is based on sensory scores (median of at least 3 evaluations made by wine experts). Each expert graded the wine quality between 0 (very bad) and 10 (very excellent).</span></p>

<p><span style="color:#212121">This popular dataset is commonly used for predicting whether a particular wine is &ldquo;good quality&rdquo; or not.</span></p>

<hr />
<p><span style="color:#212121">REFRESHER:</span></p>

<p><span style="color:#212121"><u>1. Target Variable:</u></span><span style="color:#212121"> The target variable or label of a dataset is the feature of a dataset about which you want to gain a deeper understanding.&nbsp;</span></p>

<p><span style="color:#212121">It is the variable that is, or should be the output.</span></p>

<p><span style="color:#212121">In the example of detecting spam emails, the label will be the category the email belongs to, i.e it will be either &lsquo;spam&rsquo; or &lsquo;not spam&rsquo;.</span></p>

<p><span style="color:#212121"><u>2. Input Variable:</u></span><span style="color:#212121">&nbsp; One or more variables that are used to determine (or predict) the &#39;Target Variable&#39; are known as Input Variables. They are sometimes called Predictor Variable as well.</span></p>

<p><span style="color:#212121">In the spam detector example, the features could include the following:</span></p>

<ul>
	<li style="list-style-type:disc"><span style="color:#212121">words in the email text</span></li>
	<li style="list-style-type:disc"><span style="color:#212121">sender&#39;s address</span></li>
	<li style="list-style-type:disc"><span style="color:#212121">time of day the email was sent</span></li>
	<li style="list-style-type:disc"><span style="color:#212121">email contains the phrase &quot;congrats you won $1 billion - share your bank details.&quot;</span></li>
</ul>

<hr />
<p><span style="color:#212121">Now what are the Input and Target variables in the wine detection problem? Let&rsquo;s have a look:</span></p>

<p><span style="color:#212121"><strong>Input variables:</strong></span></p>

<ol>
	<li style="list-style-type:decimal"><span style="color:#212121">fixed acidity</span></li>
	<li style="list-style-type:decimal"><span style="color:#212121">volatile acidity</span></li>
	<li style="list-style-type:decimal"><span style="color:#212121">citric acid</span></li>
	<li style="list-style-type:decimal"><span style="color:#212121">residual sugar</span></li>
	<li style="list-style-type:decimal"><span style="color:#212121">chlorides</span></li>
	<li style="list-style-type:decimal"><span style="color:#212121">free sulfur dioxide</span></li>
	<li style="list-style-type:decimal"><span style="color:#212121">total sulfur dioxide</span></li>
	<li style="list-style-type:decimal"><span style="color:#212121">density</span></li>
	<li style="list-style-type:decimal"><span style="color:#212121">pH</span></li>
	<li style="list-style-type:decimal"><span style="color:#212121">sulphates</span></li>
	<li style="list-style-type:decimal"><span style="color:#212121">alcohol</span></li>
</ol>

<p><span style="color:#212121"><strong>Output variable:</strong></span></p>

<ol start="12">
	<li style="list-style-type:decimal"><span style="color:#212121">quality (score between 0 and 10)</span></li>
</ol>

<p>&nbsp;</p>

<hr />
<p><span style="color:#212121">In this module, we&#39;ll be performing EDA on Red Wine data, you can then practice the things you learnt on White Wine data.</span></p>

<p>&nbsp;</p>