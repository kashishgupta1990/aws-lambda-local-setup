# How to debug AWS Lambda in local machine with Node.js

## Pre-Requisite:-
- NodeJs Installed [Download](https://nodejs.org)
- AWS Account [Login/Signup](https://aws.amazon.com/)
- AWS CLI should installed properly with login credentials done. [aws-cli](https://aws.amazon.com/cli/)

## Tools used:-
- Visual Studio Code [Editor](https://code.visualstudio.com/)
- Node Modules used
  - lambda-local
  - path

## Project Setup and Run
- Clone this repository [Clone](https://github.com/kashishgupta1990/aws-lambda-local-setup)
- Run `npm install`
- `local-execute.js` is the start file where you need to pass the `jsonPayload` you want to pass.
- Setting Visual Studio Code debugger to execute `local-execute.js` file first.
- `handler.js` is the actual `lambda` file which contains the serverless functions.
- Put your break-points in `handler.js` file and run your code in debug-mode available in `Visual Studio Code`
- This handler contains the code which echo back `query-parameter` you passed to it.

