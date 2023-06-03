# Serverless-website-AWS

My project is a serverless website that uses various services offered by AWS.

# Project in Brief
For hosting the website I've used AWS Amplify, 
then to run the conversion python script I've used AWS Lamda function which is invoked by an API request (AWS API Gateway) which gets triggered when we click the "Calculate" button in the website.
In addition to calculating the data, the Lamda function also sends the input data to a DynamoDB ( using IAM role to access it ) which saves the input values into a non-relational database.

# Architecture
