# Overview

# How to use

- Send email

```
awslocal ses send-email \
    --from mo3789530@gmail.com \
    --message 'Body={Text={Data="Lorem ipsum dolor sit amet, consectetur adipiscing elit, ..."}},Subject={Data=Test Email}' \
    --destination 'ToAddresses=mo3789530a@gmail.com '

```