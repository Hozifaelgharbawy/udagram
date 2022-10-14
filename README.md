# Hosting a Full-Stack Application

- Applications that are built on top of a full stack called Udagram [Link](http://hozifa-dagram.s3-website-us-east-1.amazonaws.com)

- documentation: [here](doc/README.md)

## about the Hosting (AWS)

This Udagram application was provided by Udacity.

### AWS services

- S3 (deploy Udagram application frontend)
- RDS (Database)
- Elastic Beanstalk (deploy Udagram application frontend)

### CircleCI

- [![CircleCI](https://dl.circleci.com/status-badge/img/gh/Hozifaelgharbawy/udagram/tree/master.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/Hozifaelgharbawy/udagram/tree/master)

## Requirements

### .env file

      AWS_ACCESS_KEY_ID=...
      AWS_DEFAULT_REGION=...
      AWS_SECRET_ACCESS_KEY=...
      URL=...
      POSTGRES_DB=...
      POSTGRES_HOST=...
      POSTGRES_PASSWORD=...
      POSTGRES_USERNAME=...
      PORT=...
      JWT_SECRET=...

### install dependencies

      npm run frontend:install
      npm run api:install

### build

      npm run frontend:build
      npm run api:build

### start

      npm run frontend:start
      npm run api:start


# Project Dependencies

#### Dependencies ror running it locally

- Node v16.17.0 (LTS) or more recent.
- npm 6.I4.8 (LTS) or more recent
- AWS CLI v2
- A Postgres database, prererably AWS RDS
- A s3 bucket ror hosting uploaded pictures

#### Dependencies ror running it online

Additional recommended environment dependencies :

- AWS s3 ror hosting the rrontend
- Elastic Beanstalk to install the backend ror an EC2
- CircleCI to automate it all


# Pipeline process
1. Push the updated code to Github Dev branch
2. Merge the code to main
3. CircleCI grabs the code and deploys it to AWS

This text was recognized by the built-in Ocrad engine. A better transcription may be attained by right clicking on the selection and changing the OCR engine to "Tesseract" (under the "Language" menu). This message can be removed in the future by unchecking "OCR Disclaimer" (under the Options menu). More info: http://projectnaptha.com/ocrad