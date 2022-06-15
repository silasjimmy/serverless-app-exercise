# Serverless app exercise
An exercise to deploy a serverless app in AWS by Udacity

## Create a serverless template
```sh
sls create --template aws-nodejs-typescript --path <FOLDER_NAME>
```

## Navigate to the created service
```sh
cd <FOLDER_NAME>
```

## Install dependencies
```sh
npm install
```

## Create package
```sh
sls package
```

## Deploy app
```sh
sls deploy --package .serverless
```