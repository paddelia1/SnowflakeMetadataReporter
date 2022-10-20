# SnowflakeMetadataReporter
Will help you automate creation of sql code as well as inspecting databases structures, metadata and code.
There are also a couple more utilities such as the Duplicate finder that allows examination of all duplicated values.
This Excel document requires install of the snowflake ODBC driver and the creation of an associated DSN entry to connect to your snowflake instance.

For now the duplicate finder function requires that you install a procedure to your snowflake instance. 
It can be in any database and it will let you inspect any database within the instance as long as your provide the fully qualified name of the object.

Set up the parameters

![image](https://user-images.githubusercontent.com/62514847/196827811-5f01128d-1917-4d99-a8b6-afa3ab42f7f0.png)
Build some sql code example a HASH statement

![image](https://user-images.githubusercontent.com/62514847/196828158-739453ac-84a9-45ba-80b5-cac28fb706c1.png)
Inspect duplicate data

![image](https://user-images.githubusercontent.com/62514847/196828313-76f73481-fd49-49cf-b006-43d6a119cd8f.png)
Generate DDL script for your entire database

![image](https://user-images.githubusercontent.com/62514847/196828454-d1a6e848-479b-4c1c-90b9-385285de32dc.png)

DSN

![image](https://user-images.githubusercontent.com/62514847/196828752-aa9f23bf-ae19-485d-b7d9-22e8ae6648cf.png)
