<h1>Healthcare Analytics for Doctor Visits</h1>

<h2>Project Overview</h2>

<p>
This project analyzes healthcare data to understand the factors associated with doctor visits.
The analysis explores demographic, economic, and health-related variables to identify
patterns in healthcare utilization.
</p>

<hr>

<h2>Objectives</h2>

<ul>
  <li>Analyze the distribution of doctor visits.</li>
  <li>Explore the relationship between age and doctor visits.</li>
  <li>Examine the impact of illness and health status.</li>
  <li>Analyze the relationship between income and doctor visits.</li>
  <li>Compare doctor visits across gender and insurance categories.</li>
  <li>Identify factors most strongly associated with doctor visits.</li>
</ul>

<hr>

<h2>Dataset</h2>

<p>
The dataset contains <strong>5,190 records</strong> and initially included
<strong>13 columns</strong>.
</p>

<p>
The unnecessary <code>Unnamed: 0</code> column was removed during data cleaning,
leaving 12 variables for analysis.
</p>

<table border="1" cellpadding="8">
  <tr>
    <th>Column</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>visits</td>
    <td>Number of doctor visits</td>
  </tr>
  <tr>
    <td>gender</td>
    <td>Gender of the individual</td>
  </tr>
  <tr>
    <td>age</td>
    <td>Age</td>
  </tr>
  <tr>
    <td>income</td>
    <td>Income</td>
  </tr>
  <tr>
    <td>illness</td>
    <td>Illness-related variable</td>
  </tr>
  <tr>
    <td>reduced</td>
    <td>Reduced activity</td>
  </tr>
  <tr>
    <td>health</td>
    <td>Health-related status</td>
  </tr>
  <tr>
    <td>private</td>
    <td>Private insurance status</td>
  </tr>
  <tr>
    <td>freepoor</td>
    <td>Free healthcare-related status</td>
  </tr>
  <tr>
    <td>freerepat</td>
    <td>Healthcare-related status</td>
  </tr>
  <tr>
    <td>nchronic</td>
    <td>Chronic condition status</td>
  </tr>
  <tr>
    <td>lchronic</td>
    <td>Long-term chronic condition status</td>
  </tr>
</table>

<hr>

<h2>Technologies Used</h2>

<ul>
  <li>Python</li>
  <li>Pandas</li>
  <li>NumPy</li>
  <li>Matplotlib</li>
  <li>Seaborn</li>
  <li>Jupyter Notebook / Google Colab</li>
</ul>

<hr>

<h2>Data Cleaning</h2>

<ul>
  <li>Removed the unnecessary <code>Unnamed: 0</code> column.</li>
  <li>Checked for missing values.</li>
  <li>Checked for duplicate records.</li>
  <li>Examined categorical variables.</li>
  <li>Generated descriptive statistics.</li>
  <li>Reviewed data types and dataset structure.</li>
</ul>

<hr>

<h2>Key Findings</h2>

<table border="1" cellpadding="8">
  <tr>
    <th>Variable</th>
    <th>Correlation with Doctor Visits</th>
  </tr>
  <tr>
    <td>Reduced Activity</td>
    <td>0.403</td>
  </tr>
  <tr>
    <td>Illness</td>
    <td>0.185</td>
  </tr>
  <tr>
    <td>Health</td>
    <td>0.149</td>
  </tr>
  <tr>
    <td>Age</td>
    <td>0.124</td>
  </tr>
  <tr>
    <td>Income</td>
    <td>-0.077</td>
  </tr>
</table>

<h3>Insights</h3>

<ul>
  <li>Reduced activity showed the strongest positive correlation with doctor visits.</li>
  <li>Illness showed a positive relationship with doctor visits.</li>
  <li>Health status was positively associated with doctor visits.</li>
  <li>Age showed a weak positive correlation.</li>
  <li>Income showed a very weak negative correlation.</li>
  <li>Health-related factors showed stronger associations with doctor visits than income.</li>
</ul>

<p>
<strong>Note:</strong> Correlation does not imply causation.
</p>

<hr>

<h2>Visualizations</h2>

<h3>Distribution of Doctor Visits</h3>

<img src="images/doctor_visits_distribution.png"
     alt="Distribution of Doctor Visits"
     width="700">

<h3>Doctor Visits by Gender</h3>

<img src="images/visits_by_gender.png"
     alt="Doctor Visits by Gender"
     width="700">

<h3>Illness vs Doctor Visits</h3>

<img src="images/illness_vs_visits.png"
     alt="Illness vs Doctor Visits"
     width="700">

<h3>Correlation Heatmap</h3>

<img src="images/correlation_heatmap.png"
     alt="Correlation Heatmap"
     width="700">

<hr>

<h2>Project Structure</h2>

<pre>
Healthcare-Analytics-Doctor-Visits/
│
├── data/
│   └── healthcare_doctor_visits.csv
│
├── images/
│   ├── doctor_visits_distribution.png
│   ├── visits_by_gender.png
│   ├── age_vs_visits.png
│   ├── illness_vs_visits.png
│   ├── health_vs_visits.png
│   ├── income_vs_visits.png
│   ├── private_insurance_vs_visits.png
│   └── correlation_heatmap.png
│
├── healthcare_analysis.ipynb
├── README.md
└── requirements.txt
</pre>

<hr>

<h2>How to Run</h2>

<ol>
  <li>Clone the repository.</li>
  <li>Install the required libraries.</li>
  <li>Open the Jupyter Notebook.</li>
  <li>Run all cells sequentially.</li>
</ol>

<pre>
pip install -r requirements.txt
</pre>

<h2>Conclusion</h2>

<p>
The analysis indicates that health-related factors, particularly reduced activity,
have a stronger association with doctor visits than demographic and income-related
variables in this dataset.
</p>
