# Determine the most efficient data format for handling large data - NYC Taxi Trips

• Explored Spark Databricks with the NYC Taxi Trips project, containing data in ‘parquet’ and ‘delta’ formats across different sizes (S, M, L, XL, XXL).

• Removed all outliers using a modified Z-Score and filtered out records with 0 distance or no passengers. Performed various tasks to note execution time across different data formats and sizes.

• Computed unit profitability of the dataset to assess execution time.

• Ranked zones by traffic, passenger volume, and profitability.

• Noted the execution time of the pipeline, finding that the ‘delta’ data format performed better with XXL dataset size, indicating it saves time for tasks involving larger datasets.

---

This code represents my submission for the module **CSC8101: Engineering For AI** at Newcastle University, where I am pursuing a Master's degree in Data Science with a specialisation in Artificial Intelligence.

_NOTE: Please be aware that I have shared this code publicly to exhibit my work. Kindly refrain from directly copying and pasting it for your coursework, as doing so may lead to issues with plagiarism._
