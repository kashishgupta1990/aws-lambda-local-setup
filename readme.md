# How to debug AWS Lambda with Node.js

## Pre-Requisite:-
- NodeJs Installed [Download](https://nodejs.org)
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
- This handles contains the code which execute the `child_process` command.

