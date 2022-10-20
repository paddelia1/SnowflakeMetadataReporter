# SnowflakeMetadataReporter
Will help you automate creation of sql code as well as inspecting databases structures, metadata and code.
There are also a couple more utilities such as the Duplicate finder that allows examination of all duplicated values.
Today it search on one column while I am working on a version that will take a list of columns and use a hash to find duplicates.
This Excel document requires install of the snowflake ODBC driver and the creation of a DSN entry to connect to your snowflake instance.

For now the duplicate finder function requires that you install a procedure to your snowflake instance. 
It can be in any database and it will let you inspect any database within the instance as long as your provide the fully qualified name of the object.
