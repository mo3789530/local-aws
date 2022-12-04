# Overview 
SQS with localstack

# How to use 
- Create queue  
`awslocal sqs  create-queue --queue-name ${queue-name}`

- List of queue  
`awslocal sqs list-queues `

- Send message to queue  
`awslocal sqs send-message --queue-url http://localhost:4566/00000000000/${queue-name --message-body test`  

- Get message from queue  
`awslocal sqs receive-message --queue-url http://localhost:4566/00000000000/${queue-name`

- Get message count   
```
awslocal sqs get-queue-attributes --queue-url 'http://localhost:4566/000000000000/${queue-name' --attribute-names ApproximateNumberOfMessages --query 'Attributes.ApproximateNumberOfMessages'
```