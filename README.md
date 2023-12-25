# Transferring_data_from_S3_to_DynamoDB_using_Lambda
Optimizing Data Workflow: Creating a Robust CSV to DynamoDB Pipeline with Lambda Efficiency

# Statement: 
Develop a comprehensive end-to-end data pipeline that seamlessly ingests data from CSV files uploaded to a source S3 bucket, utilizing a Lambda function to efficiently transfer and load the data into a DynamoDB table

## AWS services used in the pipeline 
•	S3
•	DynamoDB
•	Lambda
•	CloudWatch
•	IAM  

## Architicture:
<img width="450" alt="Transferring data from S3 to DynamoDB using Lambda_Architecture" src="https://github.com/Adinarayana7008/Change_data_capture_MySQL_to_Athena/assets/68777627/1b510b47-37cb-4bc3-ac6a-fb64d2dc38aa">
 
### The pipeline primarily performs the following operation:

File uploads to an S3 bucket by users automatically trigger a Lambda function through real-time change detection using a Python script. This Lambda function adeptly processes and loads the resulting data into a DynamoDB table for seamless integration.

