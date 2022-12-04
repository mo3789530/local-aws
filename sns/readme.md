# Overview 

# How to use 
- Create topic  
`awslocal sns create-topic --name test-topic `
- List of topics
`awslocal sns list-topics`
- Subscribe topic  
`awslocal sns subscribe --topic-arn ${topic-arn} `
- List of subscribe
`awslocal sns list-subscriptions`
- Publish topic  
`awslocal sns publish --topic-arn ${topic-arn} --message "Hello SNS!"`
- Unsubscribe  
`awslocal sns unsubscribe --subscription-arn ${subscription-arn } `