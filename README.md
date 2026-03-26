<h1>Term Deposit Subscription Modeling for Retail Banking</h1>

<h2>Project overview</h2>
<p>
A bank collected customer and campaign data to understand which clients are likely to
subscribe to a long-term fixed deposit. This project uses logistic regression to predict
subscription and support more effective marketing campaigns.
</p>

<h2>Business problem</h2>
<p>
Long-term deposits are important for bank liquidity and interest management. The bank wanted to:
</p>
<ul>
  <li><b>Identify customers likely to subscribe</b> before launching campaigns.</li>
  <li><b>Reduce unnecessary calls and messages</b> to uninterested customers.</li>
  <li><b>Understand which factors</b> drive deposit decisions.</li>
</ul>

<h2>Objectives</h2>
<ul>
  <li><b>Build a logistic regression model</b> to predict deposit subscription (Y variable).</li>
  <li><b>Perform EDA</b> to understand customer and campaign characteristics.</li>
  <li><b>Evaluate model performance</b> and interpret key drivers.</li>
</ul>

<h2>Data and features</h2>
<p>
The dataset includes:
</p>
<ul>
  <li><b>Customer attributes:</b> age, job, marital status, education.</li>
  <li><b>Financial information:</b> balance, housing loan, personal loan.</li>
  <li><b>Campaign details:</b> contact type, previous contacts, outcome of past campaigns.</li>
  <li><b>Target variable:</b> Y (yes/no for term deposit subscription).</li>
</ul>

<h2>Methodology</h2>
<ul>
  <li><b>Data preprocessing:</b> cleaning, encoding categorical variables, handling outliers.</li>
  <li><b>EDA:</b> univariate and bivariate analysis of subscription behavior.</li>
  <li><b>Modeling:</b> logistic regression on scaled data.</li>
  <li><b>Evaluation:</b> confusion matrix, precision, recall, ROC curve, and AUC.</li>
</ul>

<h2>Key results</h2>
<ul>
  <li><b>Subscription probability scores</b> for each customer.</li>
  <li><b>Key drivers</b> such as age, balance, and past campaign outcomes.</li>
  <li><b>Performance metrics</b> to assess model usefulness in campaigns.</li>
</ul>

<h2>Business impact</h2>
<ul>
  <li><b>Smarter targeting:</b> focus outreach on customers with higher subscription probability.</li>
  <li><b>Cost savings:</b> fewer calls to low-probability customers.</li>
  <li><b>Higher conversion rates:</b> more efficient term deposit campaigns.</li>
</ul>
