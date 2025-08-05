<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Power BI End-to-End Module</title>
   
</head>
<body>
    <div class="container">
        <h1>Power BI End-to-End Project Module</h1>
        <p><strong>Version:</strong> 1.0</p>
        <p><strong>Last Updated:</strong> August 2025</p>

        <h2>📌 Overview</h2>
        <p>This module guides you through building a complete Power BI solution from data ingestion to report publishing. You'll connect to a data source, transform data using Power Query, build interactive visuals, and publish your report to the Power BI Service.</p>

        <h2>⚙️ Pre-requisites</h2>
        <ul>
            <li>Power BI Desktop (latest version)</li>
            <li>Basic knowledge of data modeling and DAX</li>
            <li>A Microsoft Power BI account (free or Pro)</li>
            <li>Sample dataset (e.g., SalesData.csv)</li>
        </ul>

        <h2>🗂️ Dataset Info</h2>
        <p>Example: <code>SalesData.csv</code> containing the following columns:</p>
        <ul>
            <li>OrderID</li>
            <li>Date</li>
            <li>Customer</li>
            <li>Region</li>
            <li>Product</li>
            <li>Quantity</li>
            <li>Price</li>
            <li>Sales</li>
        </ul>

        <h2>🚀 Step-by-Step Instructions</h2>
        <h3>1. Load the Data</h3>
        <ul>
            <li>Open Power BI Desktop</li>
            <li>Click <strong>Home → Get Data → Text/CSV</strong></li>
            <li>Select <code>SalesData.csv</code> and click <strong>Load</strong></li>
        </ul>

        <h3>2. Transform the Data (Power Query)</h3>
        <ul>
            <li>Click <strong>Transform Data</strong></li>
            <li>Ensure data types are correct</li>
            <li>Remove duplicates, handle missing values</li>
            <li>Create a <code>Total Sales</code> column: <code>= [Quantity] * [Price]</code></li>
            <li>Close & Apply</li>
        </ul>

        <h3>3. Build the Data Model</h3>
        <ul>
            <li>Identify relationships if you have multiple tables</li>
            <li>Use <strong>Manage Relationships</strong> if necessary</li>
        </ul>

        <h3>4. Create Visualizations</h3>
        <ul>
            <li>Bar chart: Sales by Region</li>
            <li>Line chart: Sales over time</li>
            <li>Table: Top 10 Products</li>
            <li>Slicer: Filter by Customer or Region</li>
        </ul>

        <h3>5. Write DAX Measures</h3>
        <ul>
            <li><code>Total Sales = SUM(SalesData[Sales])</code></li>
            <li><code>Avg Sales = AVERAGE(SalesData[Sales])</code></li>
            <li><code>Sales Growth % = DIVIDE([Total Sales] - [Previous Sales], [Previous Sales])</code></li>
        </ul>

        <h3>6. Format the Report</h3>
        <ul>
            <li>Use themes, consistent fonts, and colors</li>
            <li>Add a logo or title</li>
            <li>Make interactive with bookmarks, tooltips, and drill-through</li>
        </ul>

        <h3>7. Publish to Power BI Service</h3>
        <ul>
            <li>Click <strong>File → Publish → To Power BI</strong></li>
            <li>Select your workspace</li>
            <li>Go to <a href="https://app.powerbi.com" target="_blank">Power BI Service</a></li>
        </ul>

        <h3>8. Share the Report</h3>
        <ul>
            <li>Click <strong>Share</strong> in the Power BI Service</li>
            <li>Set user permissions</li>
            <li>Optionally, embed into a website or Teams</li>
        </ul>

        <h2>📘 Additional Resources</h2>
        <ul>
            <li><a href="https://learn.microsoft.com/en-us/power-bi/" target="_blank">Power BI Documentation</a></li>
            <li><a href="https://community.powerbi.com/" target="_blank">Power BI Community</a></li>
            <li><a href="https://www.youtube.com/user/mspowerbi" target="_blank">Power BI YouTube Channel</a></li>
        </ul>

        <h2>✅ Module Outcomes</h2>
        <p>By completing this module, you will be able to:</p>
        <ul>
            <li>Load and clean data in Power BI</li>
            <li>Design a star schema model</li>
            <li>Write basic and advanced DAX measures</li>
            <li>Create rich, interactive reports</li>
            <li>Publish and share your work with others</li>
        </ul>

        <hr>
        <p><strong>Author:</strong> Your Name | <strong>Contact:</strong> your.email@example.com</p>
        <p>&copy; 2025 Power BI Learning Module</p>
    </div>
</body>
</html>
