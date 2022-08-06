# A collection of Cloudformation templates 

These AWS Cloudformation templates are things I've been building to better understand AWS and Cloudformation. I'll probably also start converting them to Terraform deployments in another repo once I'm more comfortable with what I'm doing.

## 1. basicWebServer.yaml

A Minimal deployment that creates a web server.... no HTTPS at this stage.


## 2. RDSSetup.yaml

By default this Creates a publicaly accessible muti-AZ postgres RDS deployemnt and the assocciated VPC and Subnet network infrastructure for it to work.

It contains paramaters for single-AZ and private access as well.

#todo create cloudwatch log group
