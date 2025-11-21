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




