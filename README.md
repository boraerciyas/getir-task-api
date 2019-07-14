# GETİR TASK

This repo is a basic REST API task of Getir. Which is written on node.js with
 
 - Express 
 - Mongoose
 - Body Parser
 
Frameworks. And Jest is used for the testing.

**Request url:** https://getir-task-api.herokuapp.com/

**Request Method**: POST

**Request body** : 

{
"startDate":"2016-03-26",

"endDate": "2017-01-27",

"minCount": 3000,

"maxCount": 3500
}

**Headers**: Content-Type - application/json

**Response code explanation**  0: Success,
                            1: There is no record ,
                           -1: Requested parameter @parameter is not correct. Please try again! 


**Curl command for testing** : 
curl -X POST -H 'Content-Type: application/json' -i https://getir-task-api.herokuapp.com/ --data '{"startDate":"2017-01-26","endDate":"2017-01-27","minCount":3000,"maxCount":3500}'

**Test:** npm run test 
