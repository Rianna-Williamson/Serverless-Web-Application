# Serverless-Web-Application
* with AWS Lambda, Amazon API Gateway, AWS Amplify, Amazon DynamoDB, Amazon Cognito

<h3> Static Web Hosting </h3>

<b> AWS Amplify </b> hosts static web resources (including HTML, CSS, JavaScript, image files)

<h3> User Management </h3>

<b> Amazon Cognito </b> provides user management and authentication functions to secure the backend API.


<h3> Serverless Backend </h3>

<b> Amazon DynamoDB </b> provides a persistence layer where data can be stored by the API's Lambda function.


<h3> RESTful API </h3>

JavaScript executed in the browser sends and receives data from a public backend API built using <b> Lambda and API Gateway.</b>



<h2> 1. Static web hosting with continous deployment </h2>
- configure AWS Amplify to host static resources for web app with continous deployment built in. 
- All static web content managed by AWS Amplify Console (HTML, CSS, JavaScript, Images)
- End user has access to site using public URL exposed by AWS Amplify Console. (no need to run any other web servers or services)
