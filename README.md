# redshift_snowflake_sample
### To begin with creating an account on AWS & Snowlake plataforms (Freemium)

### Initially, make a fake data-set
![](snapshots/redshift_snowflake_1.png)
### After creating it, display all its items from DataFrame
![](snapshots/redshift_snowflake_2.png)

### Subsequently, I show its information as to describe each feature/column
![](snapshots/redshift_snowflake_8.png)
### Connect to redshift PaaS by their connection
![](snapshots/redshift_snowflake_22.png)
### Set AWS Credential Keys
![](snapshots/redshift_snowflake_23.png)
### The Data was split to 3 tables (citizens, address, health_care)

#### The redshift was built, and loaded with 3 dataFrames with an 'Unique code' in common
![](snapshots/redshift_snowflake_6.png)

#### Update the tables to redshift
![](snapshots/redshift_snowflake_3.png)

![](snapshots/redshift_snowflake_4.png)

![](snapshots/redshift_snowflake_5.png)
### Having uploaded the whole data to AWS Redshift, I connected to it, made queries, and joined to single table in order to data validation
![](snapshots/redshift_snowflake_9.png)
### Make a default datawarehose on Snowflake plataform
![](snapshots/redshift_snowflake_10.png)
### Using snowflake drivers in python, I create DATAWAREHOUSE, DATABASE and SCHEMA
![](snapshots/redshift_snowflake_11.png)
### Pushing the 3 same frames from Redshift to Snowflake
![](snapshots/redshift_snowflake_12.png)

![](snapshots/redshift_snowflake_13.png)

![](snapshots/redshift_snowflake_14.png)
### Testing correctly a query in SNOWFLAKE
![](snapshots/redshift_snowflake_15.png)
### The result of the query
![](snapshots/redshift_snowflake_16.png)
### View the snowflake's application
#### Create Worksheets
![](snapshots/redshift_snowflake_18.png)
#### Build  Dashboards
![](snapshots/redshift_snowflake_17.png)
### Loading Australian Dashboard using Worsheets
![](snapshots/redshift_snowflake_19.png)
### BarCharts and LineCharts
![](snapshots/redshift_snowflake_20.png)
### Scorecards
![](snapshots/redshift_snowflake_7.png)
### HeatGrids
![](snapshots/redshift_snowflake_21.png)

## Wrap up!
- Connect to RedShift(AWS) and Snowflake
- The fake-data consist of 100000 rows. Nonetheless, snowflake free has almost reached the limit of 1500 rows
- Handle with data with python
- Transform data, columns and dataframes into tables and dashboard on Snowflake
- Playing with Pandas: add rows, change dtypes of features, split and concat columns
- Create the charts of Snowflakes. Unfortunately, so far I don't know how to interactive a chart with each other 