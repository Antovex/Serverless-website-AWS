# Serverless-website-AWS

My project is a serverless website that uses various services offered by AWS.

# Project in Brief
For hosting the website I've used AWS Amplify, 
then to run the conversion python script I've used AWS Lamda function which is invoked by an API request (AWS API Gateway) which gets triggered when we click the "Calculate" button in the website.<br>
In addition to calculating the data, the Lamda function also sends the input data to a DynamoDB ( using IAM role to access it ) which saves the input values into a non-relational database.

# Demonstration
<p>The demonstration and the working has been explained in the provided link below.<br>
https://bit.ly/anto-proj-demo
</p>

# Architecture
![alt text](https://github.com/Antovex/Serverless-website-AWS/blob/main/AWS-Your-Age-in-seconds-architecture.png?raw=true)


## Feedback

If you have any feedback, please reach out to us at antaringhosal@gmail.com
