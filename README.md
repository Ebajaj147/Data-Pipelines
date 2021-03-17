**Data Pipelines for Analysis**

Here I've created and implemented a data pipeline to calculate the metrics for a fake webserver:

1. `log_generator.py` --> generates fake webserver logs.
2. `store_logs.py` --> parses the logs and stores them in a SQLite database.
3. `count_visitors.py` --> pulls from the database to count visitors to the website per day.
4. `count_browsers.py` --> pulls from the database to count unique browsers used to access the website per day.

**Usage -**

Execute the 4 scripts mentioned above, in order.

**Output -**

You should see output from `count_visitors.py` and `count_browsers.py`.

**Conclusion -**
Successfully created and implemented two basic data pipelines, and demonstrated some of the key principles of data pipelines:

1. Make each step of the process fairly small.
2. Passing data between pipelines with well defined interfaces.
3. Storing all of the raw data for later analysis.

**Overview -**
![pipelines](https://user-images.githubusercontent.com/46665472/111454669-e6810480-873a-11eb-9f7d-d21ff7dfdb97.jpeg)
