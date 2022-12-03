# Overview
local-aws is a aws emulator that runs in a docker container on your pc.

## How to run local-aws

Start with docker-compose
```
docker-compose up -d local-aws
```

Health check after start docker 
```
curl -s "http://127.0.0.1:4566/health" | jq .
```

## How to use local-aws by cli
Step 1. Install aws cli 
https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html
Step 2. Install awscli-local
```
sudo pip3 install awscli-local
```

Step3. Run awscli-local for test
```
awslocal --version
```

Setp4. Set default resion
```
export AWS_DEFAULT_REGION=ap-northeast-1
```

## Tutorial 
[S3 (shell)](./s3/shell/readme.md)  
[S3 (terraform)](./s3/terraform/readme.md)  
[lambda](./lambda/readme.md)