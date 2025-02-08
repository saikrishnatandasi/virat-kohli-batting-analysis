<!DOCTYPE html>
<html lang="en">

<body>
    <h1>Virat Kohli Batting Analysis</h1>
<h2>Project Overview</h2>
    <p>This project aims to analyze the batting performance of Virat Kohli, one of the most prominent cricketers in the world. The analysis involves web scraping to gather data, data cleaning to prepare the data for analysis, and creating an interactive Power BI dashboard for visualization.</p>

 <h2>Tools and Technologies</h2>
    <ul>
        <li><strong>Python</strong>: For web scraping and data cleaning.</li>
        <li><strong>Power BI</strong>: For data visualization and dashboard creation.</li>
    </ul>

<h2>Steps Involved</h2>

 <h3>1. Web Scraping</h3>
    <p><strong>Script</strong>: <code>web_scraping.py</code></p>
    <p><strong>Objective</strong>: Collect data on Virat Kohli's batting performance from various cricket websites.</p>
    <p><strong>Libraries Used</strong>: </p>
    <ul>
        <li><code>requests</code></li>
        <li><code>BeautifulSoup</code></li>
        <li><code>pandas</code></li>
    </ul>
    <p><strong>Process</strong>:</p>
    <ol>
        <li>Send HTTP requests to cricket data websites.</li>
        <li>Parse HTML content to extract relevant data.</li>
        <li>Store the data in a structured format (CSV).</li>
    </ol>

 <h3>2. Data Cleaning</h3>
    <p><strong>Script</strong>: <code>data_cleaning.py</code></p>
    <p><strong>Objective</strong>: Clean and preprocess the scraped data to make it suitable for analysis.</p>
    <p><strong>Libraries Used</strong>:</p>
    <ul>
        <li><code>pandas</code></li>
        <li><code>numpy</code></li>
    </ul>
    <p><strong>Process</strong>:</p>
    <ol>
        <li>Handle missing values and duplicates.</li>
        <li>Format and standardize data.</li>
        <li>Add derived metrics for enhanced analysis.</li>
    </ol>
    <h3>3. Power BI Dashboard</h3>
    <p><strong>File</strong>: <code>virat_kohli_dashboard.pbix</code></p>
    <p><strong>Objective</strong>: Create an interactive dashboard to visualize Virat Kohli's batting performance.</p>
    <p><strong>Visuals Included</strong>:</p>
    <ul>
        <li>Runs scored over the years.</li>
        <li>Batting average and strike rate.</li>
        <li>Performance in different formats (Test, ODI, T20).</li>
        <li>Comparison with other players.</li>
    </ul>

   <h2>Installation and Usage</h2>
    <ol>
        <li><strong>Clone the repository</strong>:
            <pre><code>git clone https://github.com/yourusername/virat-kohli-batting-analysis.git
cd virat-kohli-batting-analysis</code></pre>
        </li>
        <li><strong>Install dependencies</strong>:
            <pre><code>pip install -r requirements.txt</code></pre>
        </li>
        <li><strong>Run web scraping script</strong>:
            <pre><code>python web_scraping.py</code></pre>
        </li>
        <li><strong>Run data cleaning script</strong>:
            <pre><code>python data_cleaning.py</code></pre>
        </li>
        <li><strong>Open Power BI file</strong>:
            <ul>
                <li>Launch Power BI Desktop.</li>
                <li>Open <code>virat_kohli_dashboard.pbix</code>.</li>
            </ul>
        </li>
    </ol>

   
