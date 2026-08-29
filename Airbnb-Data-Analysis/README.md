<h1 align="center">🏠 Airbnb Data Analysis</h1>

<p align="center">
  Exploratory Data Analysis of Airbnb Listings using Python
</p>

<p align="center">

  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />

  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />

  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />

  <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" />

</p>

<hr>

<h2>📌 Project Overview</h2>

<p>
This project performs Exploratory Data Analysis (EDA) on an Airbnb listings dataset.
The analysis explores patterns in pricing, room types, neighbourhoods,
customer reviews, property availability, and host characteristics.
</p>

<p>
The project was developed using Python and Google Colab.
</p>

<hr>

<h2>🎯 Project Objectives</h2>

<ul>
  <li>Understand the structure of the Airbnb dataset</li>
  <li>Identify and analyze missing values</li>
  <li>Clean and prepare the dataset for analysis</li>
  <li>Analyze Airbnb room types</li>
  <li>Explore pricing patterns</li>
  <li>Identify neighbourhoods with the highest number of listings</li>
  <li>Analyze customer reviews</li>
  <li>Study property availability</li>
  <li>Compare verified and non-verified hosts</li>
  <li>Generate meaningful insights through data visualization</li>
</ul>

<hr>

<h2>📊 Dataset Information</h2>

<table>
  <tr>
    <th>Metric</th>
    <th>Details</th>
  </tr>

  <tr>
    <td>Total Listings</td>
    <td><b>102,599</b></td>
  </tr>

  <tr>
    <td>Total Columns</td>
    <td><b>26</b></td>
  </tr>
</table>

<br>

<p>The dataset contains information related to:</p>

<ul>
  <li>Listing details</li>
  <li>Host information</li>
  <li>Room types</li>
  <li>Pricing</li>
  <li>Neighbourhoods</li>
  <li>Reviews</li>
  <li>Availability</li>
  <li>Cancellation policies</li>
</ul>

<blockquote>
  Note: The complete dataset is not included in this repository due to file size limitations.
</blockquote>

<hr>

<h2>🛠️ Technologies Used</h2>

<table>
  <tr>
    <th>Technology</th>
    <th>Purpose</th>
  </tr>

  <tr>
    <td>Python</td>
    <td>Data analysis and programming</td>
  </tr>

  <tr>
    <td>Google Colab</td>
    <td>Notebook development environment</td>
  </tr>

  <tr>
    <td>Pandas</td>
    <td>Data manipulation and analysis</td>
  </tr>

  <tr>
    <td>NumPy</td>
    <td>Numerical operations</td>
  </tr>

  <tr>
    <td>Matplotlib</td>
    <td>Data visualization</td>
  </tr>

  <tr>
    <td>Seaborn</td>
    <td>Statistical data visualization</td>
  </tr>
</table>

<hr>

<h2>🔄 Project Workflow</h2>

<ol>
  <li>Import Libraries</li>
  <li>Upload Dataset</li>
  <li>Load Dataset</li>
  <li>Understand Dataset Structure</li>
  <li>Analyze Missing Values</li>
  <li>Clean the Data</li>
  <li>Perform Exploratory Data Analysis</li>
  <li>Analyze Room Types</li>
  <li>Analyze Pricing</li>
  <li>Analyze Locations</li>
  <li>Analyze Reviews</li>
  <li>Analyze Availability</li>
  <li>Analyze Host Characteristics</li>
  <li>Generate Key Insights</li>
</ol>

<hr>

<h2>🔍 Analysis Performed</h2>

<h3>🏠 Room Type Analysis</h3>

<p>
The distribution of Airbnb listings was analyzed based on different room types.
</p>

<p><b>Key Finding:</b></p>

<p>
🏆 <b>Entire home/apt</b> is the most common room type.
</p>

<hr>

<h3>💰 Pricing Analysis</h3>

<p>
Airbnb prices were analyzed across different room types and locations.
</p>

<p><b>Key Finding:</b></p>

<p>
🏆 <b>Hotel room</b> has the highest average price among the room types.
</p>

<hr>

<h3>📍 Location Analysis</h3>

<p>
Neighbourhoods were analyzed based on the number of Airbnb listings.
</p>

<p><b>Key Finding:</b></p>

<ul>
  <li><b>Bedford-Stuyvesant</b> has the highest number of Airbnb listings.</li>
  <li><b>Queens</b> has the highest average price among neighbourhood groups.</li>
</ul>

<hr>

<h3>⭐ Review Analysis</h3>

<p>
Customer engagement was analyzed using:
</p>

<ul>
  <li>Number of reviews</li>
  <li>Reviews per month</li>
  <li>Review ratings</li>
</ul>

<hr>

<h3>📅 Availability Analysis</h3>

<p>
Property availability was analyzed using the
<code>availability_365</code> feature.
</p>

<p><b>Key Finding:</b></p>

<p>
🏆 <b>Hotel room</b> has the highest average availability.
</p>

<hr>

<h3>👤 Host Verification Analysis</h3>

<p>
Verified and unconfirmed hosts were compared based on average pricing
and average number of reviews.
</p>

<table>
  <tr>
    <th>Host Verification</th>
    <th>Average Price</th>
    <th>Average Reviews</th>
  </tr>

  <tr>
    <td>Unconfirmed</td>
    <td>626.63</td>
    <td>27.54</td>
  </tr>

  <tr>
    <td>Verified</td>
    <td>623.86</td>
    <td>27.32</td>
  </tr>
</table>

<br>

<p><b>Key Finding:</b></p>

<p>
Verified and unconfirmed hosts show only minimal differences in
average pricing and reviews.
</p>

<hr>

<h2>💡 Key Insights</h2>

<ol>
  <li>The dataset contains <b>102,599 Airbnb listings</b>.</li>

  <li>
    <b>Entire home/apt</b> is the most common room type.
  </li>

  <li>
    <b>Bedford-Stuyvesant</b> has the highest number of Airbnb listings.
  </li>

  <li>
    <b>Queens</b> has the highest average Airbnb price among neighbourhood groups.
  </li>

  <li>
    <b>Hotel room</b> has the highest average price among room types.
  </li>

  <li>
    <b>Hotel room</b> has the highest average availability.
  </li>

  <li>
    Verified and unconfirmed hosts show only minimal differences
    in average pricing and reviews.
  </li>
</ol>

<hr>

<h2>📈 Visualizations</h2>

<p>The project includes visualizations related to:</p>

<ul>
  <li>Room Type Distribution</li>
  <li>Top 10 Neighbourhoods</li>
  <li>Average Price by Room Type</li>
  <li>Price Distribution</li>
  <li>Review Analysis</li>
  <li>Availability Analysis</li>
</ul>

<p>
Visualizations are available in the
<code>images</code> folder.
</p>

<hr>

<h2>📂 Project Structure</h2>

<pre>
Airbnb-Data-Analysis/
│
├── Airbnb_Hotel_Booking_Data_Analysis.ipynb
│
├── README.md
│
├── Data/
│
├── images/
│   ├── room_type_distribution.png
│   ├── top_10_neighbourhoods.png
│   ├── average_price_by_room_type.png
│   ├── price_distribution.png
│   ├── reviews_analysis.png
│   └── availability_analysis.png
│
└── presentations/
    └── Airbnb_Data_Analysis_Presentation.pptx
</pre>

<hr>

<h2>📌 Conclusion</h2>

<p>
This project demonstrates how Exploratory Data Analysis can be used
to identify meaningful patterns in Airbnb listing data.
</p>

<p>
The analysis highlights the relationship between room types, pricing,
location, availability, reviews, and host characteristics.
</p>

<p>Through this project, the following skills were applied:</p>

<ul>
  <li>Data Cleaning</li>
  <li>Data Analysis</li>
  <li>Data Visualization</li>
  <li>Python Programming</li>
  <li>Pandas</li>
  <li>Exploratory Data Analysis</li>
</ul>

<hr>

<h2>👨‍💻 Author</h2>

<p>
<b>Avx Sharma</b>
</p>
