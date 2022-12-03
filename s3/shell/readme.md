# How to use 

| Command                                         | Description                         |
| ----------------------------------------------- | ----------------------------------- |
| awslocal s3 ls                                  | lists all buckets                   |
| awslocal s3 ls s3://{bucket}/{path}             | lists all objects and prefixes      |
| awslocal s3 mb s3://{bucket}                    | create bucket                       |
| awslocal s3 rm s3://{bucket}                    | delete bucket                       |
| awslocal s3 rb s3://{bucket} --force            | force delete bucket                 |
| awslocal s3 rm s3://{bucket}/{path}             | delete object                       |
| awslocal s3 rm s3://{bucket}/{path} --recursive | delete foler                        |
| awslocal s3 cp {file_path} s3://{bucket}        | copy files from a local or a bucket |
| awslocal s3 cp {file_path} s3://{bucket}        | copy files from a local or a bucket |
