# rfid-scanner-infrastructure

This repository contains a CloudFormation Template that will spin up the infrastructure needed to run the RFID Scanner application.

After the template has completed, you will need to populate the Lambda function with the code from [rfid-lambda-get-uid-data](https://github.com/thomasphorton/rfid-lambda-get-uid-data), as well as populate the DynamoDB table with card data.
