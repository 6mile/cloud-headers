# Cloud Headers
This is a (hopefully) authoratative listing of all the HTTP headers used by the major cloud providers

## AWS

AWS Elastic Load Balancer (ELB & ALB)
- 'Server: awselb/2.0'

aws-cloudfront
- 'X-Amz-Cf-Id:'
- 'X-Amz-Cf-Pop:'


aws-codebuild
- "arn: arn:aws:codebuild"
- 'X-Amz-Meta-Codebuild-Buildarn:'
- 'x-amz-meta-codebuild-buildarn:'
- 'X-Amz-Meta-Codebuild-Content-Sha256:'
- 'x-amz-meta-codebuild-content-sha256:'
- 'X-Amz-Meta-Codebuild-Content-Md5:'
- 'x-amz-meta-codebuild-content-md5:'

aws-api-gateway
- 'X-Amz-Apigw-Id:'

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
