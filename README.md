# Capstone Project: Serverless API & Containerized Web App
## Create new repository
Created a new repository in GitHub called AWS-PROJECTCAPSTONE-1

## Clone the repository 
`https://github.com/vokemwa/AWS-ProjectCapstone-1.git`

## Create the files
Create the files and folders in VS code i.e. lambda-api/index.js, webapp/Dockerfile, infrastructure.yaml anf README.md files

## Save the files and push to repository
`git add .`
`git commit -m`
`git push`

## Create Lambda
* Search for Lambda in AWS console
* Create lambda function
* Keep author from scratch seleted
* Give a function name 'CapstoneProject1-backend'
* select runtime 'Node.JS 24.x'
* Architecture use the default 'x86_64'
* click Create Function Button
* Edit the source code and paste the sample we were given
* Click deploy

![alt text](image.png)

![alt text](image-1.png)

## Create REST API
* search for REST API
* Select New API
* Give it a name 'ProjectCapstone1-API'
* End point Type 'Regional'
* IP Address Type 'IPv4'
* Click Create API button

### Create Resources
* Create Resources
* Maintain Resource Path `/`
* Resource Name `submit`
* Click Create resource

![alt text](image-2.png)

### Create Method
* Select /submit resource and click Create method
* Select Method type `POST`
* Integration Type `Lambda function`
* Select the region and the Lambda function
* Click Create method

![alt text](image-3.png)

### Deploy The API
* Click Deploy
* Select *New stage*
* Stage name `Production`
* Click Deploy

![alt text](image-4.png)

### Success REST API

![alt text](image-5.png)

