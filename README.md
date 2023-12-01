# Cloud Headers
This is a (hopefully) authoratative listing of all the HTTP headers used by the major cloud providers

## AWS

AWS Elastic Load Balancer (ELB & ALB)
- 'Server: awselb/2.0'
- 'Set-Cookie: AWSALB='
- 'Set-Cookie: AWSALBCORS='

aws-cloudfront
- 'X-Amz-Cf-Id:'
- 'X-Amz-Cf-Pop:'

aws-codebuild
- "arn: arn:aws:codebuild"
- 'X-Amz-Meta-Codebuild-Buildarn:'
- 'X-Amz-Meta-Codebuild-Content-Sha256:'
- 'X-Amz-Meta-Codebuild-Content-Md5:'

aws-api-gateway
- 'X-Amz-Apigw-Id:'
- 'X-Amzn-Remapped-Connection:'
- 'X-Amzn-Remapped-Content-Length:'
- 'X-Amzn-Remapped-Date:'

aws-kms
- 'X-Amz-Server-Side-Encryption:'

aws-xray
- 'X-Amzn-Trace-Id:'

aws-waf-captcha
- 'X-Amzn-Waf-Action:'

aws-dynamodb
- 'X-Amz-Crc32:'
- 'X-Amz-Target:'

## Oracle Cloud

This unique Oracle-assigned request ID header is passed with every response from Oracle cloud. For more information check out: https://docs.public.oneportal.content.oci.oraclecloud.com/en-us/iaas/Content/API/Concepts/usingapi.htm

- opc-request-id:
- x-oracle-apmcs-request-id:
- x-oracle-dms-ecid:
- x-oracle-dms-rid:

## Azure

Azure Front Door
- X-Azure-Ref:
- X-Azure-FDID: # A unique ID identifying customer ID in Front Door
- X-FD-HealthProbe: # A boolean identifying if the request was a backend probe

Azure Functions
- X-Azure-Ref:
- X-Ms-Clitelem:
- X-Ms-Ests-Server:

Azure Storage
- X-Ms-Request-Id:

Azure App Service App Restriction
- X-Ms-Forbidden-Ip:

Microsoft Active Directory Federation Services
- x-ms-proxy-app-id:
- x-ms-proxy-group-id:
- x-ms-proxy-subscription-id:
- x-ms-proxy-transaction-id:
- x-ms-proxy-service-name:
- x-ms-proxy-data-center:

## Heroku

Heroku 
- Set-Cookie: heroku-session-affinity=
- Server: heroku
- Reporting-Endpoints: heroku-nel=
- Nel: {"report_to":"heroku-nel","max_age":3600,"success_fraction":0.005,"failure_fraction":0.05,"response_headers":["Via"]}

Appian
- __appianCsrfToken:
- set-cookie: __appianCsrfToken=
