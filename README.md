## Anand Patel
# Project 2: Tracking User Activity

In this project, you work at an ed tech firm. You've created a service that
delivers assessments, and now lots of different customers (e.g., Pearson) want
to publish their assessments on it. You need to get ready for data scientists
who work for these customers to run queries on the data. 

# Tasks

Prepare the infrastructure to land the data in the form and structure it needs
to be to be queried.  You will need to:

- Publish and consume messages with Kafka
- Use Spark to transform the messages. 
- Use Spark to transform the messages so that you can land them in HDFS
- In order to show the data scientists at these other companies the kinds of data
that they will have access to, decide on basic business questions that
you believe they might need to answer about these data.



## Data

To get the data, run 
```
curl -L -o assessment-attempts-20180128-121051-nested.json https://goo.gl/ME6hjp
```



## Files of Interest:

- [`proj2_writeup.md`](proj2_writeup.md): My main report for the project. **Read this one first**, it will link to the Jupyter Notebook for the Spark section.
- [`proj2_pyspark_nb.ipynb`](proj2_pyspark_nb.ipynb): My Spark report for the project. Contains all commands run in Spark. **Please reference when getting to the section on Spark in the main report.** 
- [`docker-compose.yml`](docker-compose.yml)
- `Anand-Patel-history.txt`

---
  
