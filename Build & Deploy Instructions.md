# CS4800.01 Frontend Build & Deplyment Instructions

This web application was built using a React.js frontend. 
The build and deployment procedures are that of a typical React.js application,
with some environment variable setup to get the APIs working properly.

## AWS Amplify Deployment Instructions

This web application was meant to be deployed on AWS Amplify as part of a serverless application.

Deployment using AWS Amplify is incredibly straightforward. 
Simply connect the github repository to AWS Amplify. 
It should automatically detect the appropriate build settings.

Two environment variables are required:
- REACT_APP_GOOGLE_MAPS_API_KEY. This should be set to a valid Google Maps JavaScript API key.
- REACT_APP_API_URL. This is the base URL of this application's backend API.

These can be set in the "Environment variables" section in AWS Amplify.

## Local Build Instructions

These are the instructions for running or building locally, for development or other applications.

Make sure Node.js is installed: https://nodejs.org/en/

Clone the github repo locally: `git clone https://github.com/AaronJimenezCPP/cs4800.01-aws-webapp.git`

The two environment variables are still required:
- REACT_APP_GOOGLE_MAPS_API_KEY. This should be set to a valid Google Maps JavaScript API key.
- REACT_APP_API_URL. This is the base URL of this application's backend API.

The easiest way to add these is to create a file in the root diretory named `.env.local` and insert the following:

```
REACT_APP_API_URL = "[Backend API URL]"
REACT_APP_GOOGLE_MAPS_API_KEY = "[Google Maps API Key]"
```

`cd` into the directory and install npm package dependencies with `npm install`

From here you can run a development environment using `npm start`

Or you can build the application using `npm run build`

