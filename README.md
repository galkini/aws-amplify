![Alt text](/serverless_app_with_AWS_Amplify.png)

Project description, deploy react app on AWS Amplify, with frontend, and backend, using Cognito, DynamoDB, and API AWS AppSync

1.	Install Node.js, and npm on your computer, and create an empty react application (npx create-react-app)
2.	Create a GitHub repository and push there the initial code of react application
3.	Create an Amplify App in Amplify Studio. 
a.	Start with backend (build an app with Gen 1 tools), create role for Amplify to access the backend, and checkmark the CI/CD option
b.	and then add frontend, when GitHub branch as a source. 
4.	Install and configure Amplify CLI access
5.	Set up users authentication option for your app (Cognito service called by Amplify), then test the updated frontend locally
6.	Create database and API to access it
a.	Create a DynamoDB table
b.	Create the AWS AppSync API
c.	Create the GraphQL operations in a folder located at src/graphql
7.	Deploy the changes to the backend (amplify push –y)
8.	Make final modification to the App code, and test the application locally 
9.	Create storage at the backend to store the images, and 
10.	Push to the GithHub, the frontend final app changes, that will initialize automated frontend redeployment (CI/CD)
11.	Run the app via global URL provided by AWS Amplify
