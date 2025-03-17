# ETL-Panda-AzurePgAdmin

eate a Python function that takes a Pandas DataFrame as input and performs the following transformations:



Iterate through each column name.
Convert the column name to lowercase.
Replace any spaces in the column name with underscores (_).
Example: "Time Uploaded" becomes "time_uploaded".




Access the "reading_time" column.
For each value in the column, remove the string " min read" from the end.
Ensure that the remaining value in the column is converted to the appropriate datatype, probably an integer.




Access the "article_content" column.
For each value in the column, replace all occurrences of the newline character (\n) with an empty string ("").




After the transformations, ensure that each column has the correct data type (e.g., integer, string, date, etc.). You might need to use Pandas functions like astype() to enforce these data types.
Determine the appropriate data types for each column based on the data that it contains.


Open pgAdmin.
Create a new server connection using the provided credentials:
