# AWS- Image recognition as a Service
 The aim of this project was to develop a cloud app whch will provide Image Recognition as a service to users by using the AWS cloud resources to perform deep learning on images provided by the users.
 
The deep learning model was provided in an AWS image (ID: ami-07303b67, Name: imageRecognition, Region: us-west-1a). This application invokes this model to perform image recognition on the received images.

The application will handle multiple requests concurrently. It will automatically scale out when the request demand increases, and automatically scale in when the demand drops.

AWS services used in the project are

* Elastic Compute Cloud (EC2)

* Simple Queue Service (SQS)

* Simple Storage Service (S3)

Further details are provided in the report.

# Web-Tier-AWS
