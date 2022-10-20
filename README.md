# End-to-End-Data-Engineering-Twitter-Project


![image](https://user-images.githubusercontent.com/55424201/196932003-50cfaae8-3e92-4088-a6b3-fc77e1deff45.png)

Taking the data from Twitter API and making an ETL with airflow on an EC2 machine and writing the data into the s3 Bucket
in this project:
- wrote an ETL script to get the data from Twitter API
- wrote a dag script for the airflow
- launch an EC2 machine 
- made IAM role to the machine to get access and to be able to write to s3 Bucket
- edit the security group to make access to my ib
- connected to the machine with ssh  
- install airflow and the packages in the machine
- opened the airflow and run the dag
