Every SQL query line ends with a semi-colon (;) however, it is not compulsory to add this. But for easy readability, it is advised that you add this.
*****************************
You must always separate your clause and its components with a space, otherwise, you would get a Syntax Error. For instance, it is SELECT 2+3 and not SELECT2+3
*****************************
When writing complex queries with SQL, always separate each query with a comma (,) and at the end of your query, add a semi-colon or you would get a Syntax Error. For instance, it is SELECT 2+3, 3+5, 5+7; and not SELECT 2+3 3+5 5+7
*****************************
If you're writing an SQL query in a Jupyter notebook, each line of query must always begin with: %sql so that the system knows you're writing an SQL query. Failure to add this results in a syntax error.
*****************************