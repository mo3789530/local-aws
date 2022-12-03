# Required
Terraform 1.0.7
### How to install terraform 
Install tfenv https://github.com/tfutils/tfenv

After install tfenv
```
tfenv install 1.0.7
tfenv use 1.0.7
```

# Run terrafrom 
```
export TF_VAR_bucket_name=<bucket_name>
terraform init
terraform plan 
terraform apply
```

Create the s3 bucket after run terrafrom apply
