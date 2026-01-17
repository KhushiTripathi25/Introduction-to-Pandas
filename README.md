
<html>
<body>
<center>
    <img src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Pandas_logo.svg" 
         alt="Pandas Logo" width="200">
</center>

<h1>Introduction to Pandas</h1>

<p>
Pandas is a popular Python library used for data manipulation and data analysis.
It provides easy-to-use data structures for working with structured data.
</p>

<h2>Why Pandas?</h2>
<ul>
    <li>Easy handling of tabular data</li>
    <li>Fast and efficient data processing</li>
    <li>Widely used in Data Analytics and Data Science</li>
    <li>Supports CSV, Excel, SQL, and JSON files</li>
</ul>

<h2>Core Data Structures</h2>
<ul>
    <li>Series – One-dimensional data structure</li>
    <li>DataFrame – Two-dimensional table of data</li>
</ul>

<h2>Uses of Pandas</h2>
<ul>
    <li>Data cleaning and preprocessing</li>
    <li>Handling missing values</li>
    <li>Filtering and sorting data</li>
    <li>Data analysis and reporting</li>
    <li>Preparing data for machine learning</li>
</ul>

<h2>Basic Pandas Syntax</h2>

<p>Import Pandas:</p>
<pre>
import pandas as pd
</pre>

<p>Create a DataFrame:</p>
<pre>
data = [[1, 20], [2, 22], [3, 21]]
df = pd.DataFrame(data, columns=["student_id", "age"])
print(df)
</pre>

<p>Read a CSV file:</p>
<pre>
df = pd.read_csv("data.csv")
</pre>

<p>Basic Operations:</p>
<pre>
df.head()
df.info()
df.describe()
</pre>


</body>
</html>
