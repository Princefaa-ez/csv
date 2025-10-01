
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
 
</head>
<body>
  <div>
    <header>
      <h1>CSV & JSON Data Repository</h1>
      <p>A compact collection of CSV and JSON files served raw from this repository for practice fetching and working with remote data.</p>
    </header>
    <section>
      <h2>Purpose</h2>
      <p>This repository provides small, well-structured <strong>.csv</strong> and <strong>.json</strong> files for personal use and learning. Use these files to practice loading data from raw GitHub URLs in tools like <code>pandas</code>, browser fetch requests, or any data-processing pipeline.</p>
    </section>
    <section>
      <h2>Repository structure</h2>
      <ul>
        <li><code>/data/</code> — CSV files (comma-separated)</li>
        <li><code>/json/</code> — JSON example files</li>
        <li><code>/README.md</code> — original markdown readme (this HTML mirrors it)</li>
      </ul>
      <h3>Notes</h3>
      <ul>
        <li>Files are lightweight and safe for testing.</li>
        <li>Intended for learning — feel free to fork and modify.</li>
      </ul>
    </section>
    <section>
      <h2>Quick links</h2>
      <p>Replace <code>username</code> and <code>repo</code> with your GitHub info.</p>
      <pre><code>Raw CSV URL:
https://raw.githubusercontent.com/princefaa-ez/csv/main/audi.csv

Raw JSON URL:
https://raw.githubusercontent.com/username/repo/main/json/example.json
</code></pre>
    </section>
    <section>
      <h2>Examples</h2>
      <p>Copy the code blocks below and substitute the raw file URLs from your repository.</p>
      <h3>Python (pandas)</h3>
      <pre><code>import pandas as pd

url = "https://raw.githubusercontent.com/princefaa-ez/csv/main/audi.csv"
df = pd.read_csv(url)
print(df.head())
</code></pre>
      <h3>JavaScript (fetch)</h3>
      <pre><code>fetch("https://raw.githubusercontent.com/username/repo/main/json/example.json")
  .then(res => res.json())
  .then(data => console.log(data))
  .catch(err => console.error(err))
</code></pre>
      <h3>cURL (download)</h3>
      <pre><code>curl -O https://raw.githubusercontent.com/princefaa-ez/csv/main/audi.csv
</code></pre>
    </section>
    <section>
      <h2>Use cases</h2>
      <ul>
        <li>Experimentally learning <code>pandas</code> and dataframes</li>
        <li>Testing front-end fetch requests and JSON parsing</li>
        <li>Prototyping small visualizations with sample data</li>
        <li>Teaching or sharing minimal datasets with others</li>
      </ul>
    </section>
    <section>
      <h2>Contributing</h2>
      <p>Although this is primarily a personal resource, pull requests are welcome if you have small, well-documented datasets to add. Please keep files small &amp; well-formed and add a short description for each new file.</p>
      <h3>Guidelines</h3>
      <ul>
        <li>Prefer CSVs under ~1 MB.</li>
        <li>Include a header row for CSV files.</li>
        <li>JSON files should be UTF-8 and properly formatted.</li>
      </ul>
    </section>
    <footer>
      <p>Made for practicing data access via raw GitHub URLs — happy coding!</p>
    </footer>
  </div>
</body>
</html>
