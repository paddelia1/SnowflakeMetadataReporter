# SnowflakeMetadataReporter
Will help you atomate creation of sql code as well as inspecting databases structures, metadata and code.
There are also a couple more utilities such as the Duplicate finder that allows examination of all duplicated values.
Today it search on one column while i am working o a version that will tak a list of column and use a hash to find duplicates.
This Excel document requires install of the snowflake ODBC driver.

For now the duplicate finder function requires that you install a procedure to your snowflake instance. it can be in any database and it will let you inspect any database as long as your provide the fully qualified name of the object.
