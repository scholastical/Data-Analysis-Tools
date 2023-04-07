The attached python file showed how to create an engine and connect to a SQL database. 
First,import required python libraries (pandas, numpy, create_engine, pymysql). 
Create the engine using create_engine() and connect the string using engine.connect(). THis gives access to the SQL database directly from the Jupyter notebook enviroment.
Now, import the SQL dataset  using pd.read_sql (in this case, the dataset is 'vgsales')
Two critical questions examined are: 
(1) Was the Average of Global Sales Higher before or after 2005?
(2) Create a new column that labels records before 2005 as 'pre-2005' and after 2005 as 'post-2005'
