### How to create lambda in LocalStack
1. Create lambda function   
e.g. `touch lambda.js`  
1. Create zip file from created lambda function  
e.g, ` zip lambda.zip lambda.js`  
1. Deploy to LocalStack  
```
awslocal lambda create-function --function-name ${function-name} --runtime nodejs16.x --region ap-northeast-1 --zip-file fileb://lambda.zip  --handler lambda.handler
```

1. Test
List of lambda functions
```
 awslocal lambda list-functions --region ap-northeast-1
```
Execute lambda function by cli
```
awslocal lambda invoke --function-name ${function-name}  response.json --region ap-northeast-1
```
Delete lambda function
```
 awslocal lambda delete-function --function-name ${function-name} --region ap-northeast-1
```

