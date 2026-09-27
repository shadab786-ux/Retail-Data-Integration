<h1>Retail Data Integration & Analysis</h1>
<h2>Overview:</h2>
<p>This project processes, cleans, and analyzes a dataset of 100,000 FMCG retail transaction records (2024). It validates financial metrics (revenue, cost, and profit margins), handles missing customer demographics, and generates key business insights across cities, categories, brands, and sales channels.</p>
<h2>Dataset Summary:</h2>
<h4>Total Records:</h4> 
<p>100,000 rows, 21 initial attributes</p>
<h4>Primary Metrics:</h4> 
<p>Invoice ID, Transaction Date, City, Store Format, Category, Brand, Sales Channel, Payment Mode, Units Sold, Cost Price, Selling Price, Stock on Hand, Reorder Level, and Lead Time.</p>
<h4>Customer Demographics:</h4>
<p>Customer Age, Gender, and Loyalty Status.</p>
<h1>Key Features & Workflow:</h1>
<h4>1)Data Cleaning & Preprocessing</h4>
<h4>Duplicate Check:</h4><p> Verified and dropped duplicate transaction records.</p>
<h4>Missing Value Imputation:</h4>
<p>a)<b>Customer_Age:</b> Imputed missing values using the median age.</p>
<p>b)<b>Customer_Gender:</b> Imputed missing entries with 'Unknown'.</p>
<h4>Datetime Conversion:</h4><p>Parsed invoice timestamps into dedicated temporal features (Year, Month, Month_Name, Day, Day_Name).</p>
<h4>Financial Metric Validation:</h4><p>Calculated and cross-verified raw dataset figures using the following logic:</p>
<p>a)Calculated Revanue= Units x Selling Price
<br>
b)Calculated cost=Units x Cost price
<br>
c)Calculated Margin=Calculated Revanue - Claculated Cost</p>
<h4>3)Exploratory Data Analysis (EDA)</h4>
<p><b>a)<High-Level Financial Performance:/b> Overall revenue, cost, margin, and total volume sold.</p>
<p><b>b)City & Regional Performance:</b>Breakdown of total revenue across key Indian metro cities (Kolkata, Delhi, Hyderabad, Chennai, Pune, Mumbai, Ahmedabad, Bengaluru). </p>
<p><b>c)Category & Brand Analysis:</b>Performance tracking across product categories (Grocery, Home Care, Snacks, Beverages, Dairy, etc.) and brands (Nestle, PepsiCo, ITC, Tata, Britannia, Amul, Parle, HUL).</p>
<p><b>d)Fulfillment & Channel Insights:</b>Sales channel performance (Online, Offline, Omnichannel) and payment mode preferences.</p>
<h4>Technical Stack:</h4>
<p><b>a)Language: </b>Python</p>
<br>
<p><b>b)Libraries:</b> pandas, numpy, matplotlib, seaborn</p>
<p><b>c)Environment:</b> Jupyter Notebook / Google Colab</p>
<h4>Key Highlights & Performance Output:</h4>
<p><b>a)Total Revenue Generated:</b>₹39,335,134.98</p>
<p><b>b)Total Operational Cost:</b>₹31,461,449.33</p>
<p><b>c)Total Net Profit / Margin:</b>₹7,873,685.66</p>
<p><b>d)Total Units Sold:</b>299,829 units</p>








