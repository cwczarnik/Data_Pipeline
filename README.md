# Data Pipeline Exploration


Looking at a generated log system for a website and analyzing trends in users by building a data pipeline.
The log generation can go on as long as possible and can be stopped when enough data has been created.


The pipeline uses SQLITE to make a database and store information.

Then by extracting the information from the database it performs analytics.

Two examples of daily metrics are measured: the daily unique ips and the daily unique browsers.

This is based off of https://github.com/dataquestio/analytics_pipeline
