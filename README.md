
<h2 align="center">Modern Java Apps with AWS </h1>

This will be the repo for the Coursera <a href="https://www.coursera.org/learn/building-modern-java-applications-on-aws">"Building Modern Java Applications on AWS"</a> program. 
In this course, we will be covering how to build a modern, greenfield serverless backend on AWS. <br>

The course material is divided in 6 weeks, each one with its respective lab.

<h2>Week 1</h2>

Goals:

   * Explain the benefits of AWS Cloud9
   * Discover four ways to interact with AWS
   * Explain the components of the Serverless Application Model
   * Use SDK and command line tools to create a secure Amazon S3 website

**Lab 1**: Create a static  Amazon S3 website with a bucket policy that restricts access to the website via IP Address. 
The website will be created using the AWS SDK and AWS CLI.


<h2>Week 2</h2>

Goals:
  
  * Describe API driven development
  * Explore API Gateway concepts and terminology
  * Use API Gateway to create three mock endpoints
  * Describe the benefits of Amazon Cognito
  * Build Amazon Cognito User Pools to authenticate users

**Lab 2**: Setup mock backend API using Amazon API Gateway REST APIs. 
You will setup 3 API endpoints using the AWS SDK and AWS CLI, these endpoints will respond to requests with mocked data. 
You will test this mock API using the website setup in Lab 1 make AJAX calls to the mock API.


<h2>Week 3</h2>
Goals:

  * Explore AWS Lambda concepts and terminology
  * Describe how the push and pull models invoke Lambda functions
  * Describe how to configure Lambda to meet your security and compliance   objectives
  *  Update Amazon API Gateway resources to point to Lambda functions

**Lab 3:** Secure the API that was built in Lab 2 by adding authentication via Amazon Cognito User Pools.

<h2>Week 4</h2>
Goals:

  * Explore AWS Step Functions concepts and terminology
  *  Explain how AWS Step Functions integrate with other AWS services
  *  Differentiate between Standard and Express Step Functions
  *  Explain how Step Functions, SQS, SNS, and EventBridge help you use event driven architecture for your application
  *  Use AWS Step Functions to orchestrate functions in parallel and in series

**Lab 4:** Create AWS Lambda functions to host the backend for your API. You will then configure the secured API built in Lab 3 to trigger to the lambda functions, 
instead of using mock integrations.

<h2>Week 5</h2>
Goals:

  * Explain the benefits of a system with observability
  * Explore AWS X-Ray concepts and terminology
  * Explore how CloudWatch logs integrate with API Gateway, Step Functions, and Lambda

**Lab 5:** Create an asynchronous state machine using AWS Step Functions for a reporting feature of the API. 
You will then configure the API to run this state machine when a request hits an API endpoint you built in the previous labs.

<h2>Week 6</h2>
Goals:

  * Describe the benefits of Edge-optimized endpoints
  * Explain how API Gateway Response Caching improves endpoint performance
  * Describe how to improve Lambda performance
  * Explain the benefits of Lambda Layers
  * Explore API Gateway Proxy for AWS services and HTTPS APIs
  * Use AWS X-Ray and API Gateway to optimize your application
  
**Lab 6:** Use AWS X-Ray to trace requests through your distributed application. 
You will also make improvements to your application using various AWS service features like Amazon API Gateway Response Caching, as well as code modifications. 
Then you will test and view the performance improvements in the AWS X-Ray Console.

<hr>

<h2> Here Be Dragons </h2>

The idea to cover all the material is to create a 'Dragon Reporting System' where users can retrieve 
and report dragon sightings using http requests and all the AWS technologies mentioned previously.

