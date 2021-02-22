# Amplify - My Amazon S3 Drive

**High level infrastructure architecture**

![Amplify - My Amazon S3 Drive](images/diagram.png)

## Stack

Summary of what the stack looks like:

* **Front-end** - React as the core framework, Amplify for Auth UI component and AWS integration.
* **Data** - All data is modeled after GraphQL types and stored in DynamoDB.
* **Storage** - The files are stored in Amazon S3 using the Amplify libraries.
* **API** - GraphQL is managed by AppSync and also acts as an API Hub to interact with other services.
* **Auth** - Cognito provides JSON Web Tokens (JWT) and along with AppSync fine-grained authorization on what data types users can access.
* **Analytics** - Amazon Pinpoint allows to collect analytics data from React application.

## Deployment

To get started with the **My Amazon S3 Drive** sample application, you can deploy into your AWS Account using the following button.

[![amplifybutton](https://oneclick.amplifyapp.com/button.svg)](https://console.aws.amazon.com/amplify/home#/deploy?repo=https://github.com/aurbac/amplify-my-amazon-s3-drive)