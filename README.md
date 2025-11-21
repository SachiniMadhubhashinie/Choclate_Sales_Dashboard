# Choclate_Sales_Dashboard
This project analyzes historical sales data for a chocolate company to uncover key trends, evaluate product and regional performance, and assess sales efficiency. Using  Excel, and Power BI , the analysis highlights top-performing products, sales patterns, cancellation rates, and seasonal trends, providing actionable insights to optimize marketing, inventory, and sales strategies.

<h2>Project Overview</h2>
<p>
This project focuses on analyzing historical sales data for a chocolate company to identify key trends, evaluate product and regional performance, and assess the efficiency of the sales process. The primary goal is to transform raw transaction data into actionable business intelligence that can inform strategic decisions for inventory, marketing, and sales team management.
</p>

<h2>Problem Statement</h2>
<p>
The business requires a clear understanding of what drives sales performance. Specifically:
</p>
<ul>
  <li>What are the top-performing products, salespersons, and countries in terms of revenue and volume (boxes sold)?</li>
  <li>Where are the underperforming areas that require focused strategic intervention?</li>
  <li>How does the "Order Status" (e.g., Delivered vs. Cancelled) impact overall financial health, and what are the primary drivers of cancellations?</li>
  <li>When are the peak sales periods (seasonality/time series analysis)?</li>
</ul>

<h2>Technology Stack</h2>
Data Storage:CSV file <br>
Visualization:Power BI

<h2>Key Performance Indicators (KPIs)</h2>
<p>These are the core metrics that will be measured, analyzed, and tracked:</p>
<table border="1" cellspacing="0" cellpadding="5">
  <thead>
    <tr>
      <th>KPI</th>
      <th>Formula / Calculation</th>
      <th>Business Significance</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Total Revenue</td>
      <td>SUM of Amount</td>
      <td>The primary measure of financial success.</td>
    </tr>
    <tr>
      <td>Total Volume</td>
      <td>SUM of Boxes</td>
      <td>Measures physical units sold, useful for inventory planning.</td>
    </tr>
    <tr>
      <td>Cancellation Rate</td>
      <td>(COUNT of 'Cancelled' orders / Total COUNT of orders) * 100</td>
      <td>Efficiency of the sales and logistics pipeline; high rates indicate problems.</td>
    </tr>
    <tr>
      <td>Average Order Value (AOV)</td>
      <td>Total Revenue / Total COUNT of orders</td>
      <td>Indicates the quality or size of an average transaction.</td>
    </tr>
    <tr>
      <td>Revenue per Salesperson</td>
      <td>Total Revenue / COUNT of unique Sales Person</td>
      <td>Measures individual team performance.</td>
    </tr>
  </tbody>
</table>


<h2>Chart Requirements and Analysis</h2>
<p>To answer the Problem Statement, the analysis should produce the following key visualizations:</p>
<table border="1" cellspacing="0" cellpadding="5">
  <thead>
    <tr>
      <th>Chart Type</th>
      <th>Analysis Goal</th>
      <th>Data Columns Required</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Bar Chart</td>
      <td>Top N Products by Revenue (Pareto Analysis)</td>
      <td>Product, Amount</td>
    </tr>
    <tr>
      <td>Geographic Map</td>
      <td>Total Revenue by Country</td>
      <td>Country, Amount</td>
    </tr>
    <tr>
      <td>Line Chart</td>
      <td>Revenue Trend Over Time (Monthly/Quarterly)</td>
      <td>Date, Amount</td>
    </tr>
    <tr>
      <td>Stacked Bar Chart</td>
      <td>Order Status Breakdown per Product/Salesperson</td>
      <td>Product or Sales Person, Order Status, Amount</td>
    </tr>
    <tr>
      <td>Scatter Plot</td>
      <td>Relationship between Boxes (Volume) and Amount (Revenue)</td>
      <td>Boxes, Amount</td>
    </tr>
  </tbody>
</table>


<h2>Key Insights & Recommendations</h2>
<p>Based on a typical analysis of sales data, the following insights and recommendations could be derived:</p>

<h3>Key Insights</h3>
<ul>
  <li><strong>Product Contribution:</strong> 'White Choc' and 'Baker's Choco Chips' generate 45% of total revenue, despite representing only 20% of product SKUs.</li>
  <li><strong>Geographic Performance:</strong> USA contributes 60% of sales volume but has a lower Average Order Value (AOV) compared to Canada, suggesting a focus on higher-volume, lower-price items.</li>
  <li><strong>Process Efficiency:</strong> Overall Cancellation Rate is 8%, but spikes to 15% for orders handled by Salesperson X, indicating a specific performance or data entry issue.</li>
  <li><strong>Seasonal Trend:</strong> Sales revenue peaks in Q4 (October-December), indicating strong holiday sales dependency.</li>
</ul>

<h3>Recommendations</h3>
<ul>
  <li><strong>Focus Investment:</strong> Allocate 60% of marketing budget to Top 3 Products (including 'White Choc') to capitalize on market demand.</li>
  <li><strong>Targeted Strategy:</strong> Investigate higher AOV in Canada and replicate the sales strategy in the USA (e.g., promotional bundles, focus on premium products).</li>
  <li><strong>Sales Training/Audit:</strong> Review and train Salesperson X; audit their sales entries to address high cancellation rate.</li>
  <li><strong>Mitigate Seasonality:</strong> Launch a Q2 promotional campaign (e.g., 'Summer Snack Pack') to stabilize sales and reduce dependency on year-end peaks.</li>
</ul>





