<h1> Predict-The-Happiness !!</h1> <br>
<p> https://www.hackerearth.com/challenge/competitive/predict-the-happiness/machine-learning/predict-the-happiness/ </p>
<p> This was a contest to predict whether costumers were happy or not about a hotel and their service from their reviews. </p>
<hr />
<h3><a href="https://he-s3.s3.amazonaws.com/media/hackathon/predict-the-happiness/predict-the-happiness/f2c2f440-8-dataset_he.zip">Download Dataset</a></h3>
<h3>Data Description</h3>
<p>You are given three files to download: train.csv, test.csv and sample_submission.csv 
The training data has 38932 rows and test data has 29404 rows.</p>
<table class="pd-table">
<thead>
<tr>
<th>Variable</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>User_ID</td>
<td>unique ID of the customer</td>
</tr>
<tr>
<td>Description</td>
<td>description of the review posted</td>
</tr>
<tr>
<td>Browser_Used</td>
<td>browser used to post the review</td>
</tr>
<tr>
<td>Device_Used</td>
<td>device used to post the review</td>
</tr>
<tr>
<td>Is_Response</td>
<td>target Variable</td>
</tr>
</tbody>
</table>
<hr />
<h3>Submission</h3>
<p>A participant has to submit a csv file containing User_ID and predicted labels in a csv format. Check the sample submission file for format.</p>
<p></p><pre class="prettyprint"><code>User_ID, Is_Response
id80132,happy
id80133,not_happy
id80134,not_happy
id80135,not_happy
id80136,happy
</code></pre>
<hr />
<h3>Evaluation Metric</h3>
<p>Submission will be evaluated based on Accuracy score. Higher the better. To know more, <a href="https://en.wikipedia.org/wiki/Evaluation_of_binary_classifiers">read here</a>.</p>
<hr />
<h3>Scripts <br /></h3>
<ul>
<li>XGBoost and NaiveBayes (R) - <a href="https://github.com/HackerEarth-Challenges/Happiness-ML-Challenge/blob/master/xgb_nb.R">Click Here</a> </li>
<li>CatBoost, LightGBM, NaiveBayes (Python) - <a href="https://github.com/HackerEarth-Challenges/Happiness-ML-Challenge/blob/master/LGB_CB_Python.ipynb">Click Here</a></li>
</ul>
