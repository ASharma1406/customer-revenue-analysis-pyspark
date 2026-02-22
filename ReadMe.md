# *Customer Revenue Analysis*



### ***Overview***

This project analyzes retail customer transaction data using PySpark to identify purchasing patterns, revenue drivers, and high-value customer segments. The analysis is implemented in a distributed computing environment to demonstrate scalable data processing and Spark-based analytics.



The notebook (customer\_revenue\_analysis.ipynb) showcases end-to-end data handling, including data validation, transformation, aggregation, and business insight generation using Spark DataFrame APIs and Spark SQL.



#### ***Objective***

* Analyze customer purchase behavior at scale
* Identify top revenue-generating categories
* Detect high-value customers
* Evaluate demographic and location-based trends
* Generate actionable insights for revenue optimization



#### ***Technology Stack***

* PySpark
* Spark SQL
* Python
* Jupyter Notebook
* Distributed Data Processing Concepts



#### ***Dataset Attributes***

The dataset includes the following attributes:

* Customer ID
* Age
* Gender
* Item Purchased
* Category
* Purchase Amount (USD)
* Location
* Size



#### ***Implementation Details***

##### *1. Spark Environment Setup*

* Initialized SparkSession
* Loaded dataset into Spark DataFrame
* Validated schema and data types

##### *2. Data Cleaning \& Validation*

* Checked and handled null values
* Verified data consistency
* Performed duplicate validation
* Applied necessary type casting

##### *3. Data Transformation*

* Applied grouping and aggregation
* Computed total revenue metrics
* Generated customer-level and category-level summaries

##### *4. Customer-Level Analysis*

* Total spending per customer
* Average purchase amount
* Identification of high-value customers

##### *5. Category \& Revenue Analysis*

* Revenue by product category
* Contribution percentage of each category
* Identification of top-performing segments

##### 6\. Demographic \& Location Analysis

* Revenue distribution by gender
* Age-based purchasing trends
* Location-wise revenue contribution

##### 7\. Spark SQL Analytics

* Created temporary views
* Executed SQL-based aggregations
* Derived business insights using structured queries



### ***Key Outcomes***

* Identified revenue-driving categories and customers
* Analyzed demographic purchasing behavior
* Evaluated revenue distribution across regions
* Provided data-backed recommendations for business optimization

### ***How to Run***

1. Install dependencies:

pip install pyspark



2\. Ensure Java is installed and properly configured.

3\. Launch Jupyter Notebook:

jupyter notebook

4\. Open and execute:

customer\_revenue\_analysis.ipynb



### ***Business Relevance***

* This project demonstrates practical application of PySpark in:
* Scalable data processing
* Distributed aggregation
* Revenue analytics
* Customer segmentation foundations
* Data-driven decision support



***Author***



Aditi Sharma

Data Analyst | PySpark | SQL | Data Engineering Enthusiast



GitHub: https://github.com/ASharma1406

