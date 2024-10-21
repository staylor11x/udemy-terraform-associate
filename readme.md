# Repo for practicing terraform concepts

 based on: https://github.com/btkrausen/hashicorp

## Setup

Create an AWS account with an IAM user. Then create two keys for the IAM user

In bash add the following:

`
export AWS_ACCESS_KEY_ID="<YOUR ACCESS KEY>"  
`
 
`
export AWS_SECRET_ACCESS_KEY="<YOUR SECRET KEY>"  
`

## Basic Terraform commands

Initialise terraform: `terraform init`

Preview the changes: `terraform plan`

Apply the configuration: `terraform apply -auto-approve`

Show the current configuration: `terraform show`

Alternativley: `terraform state list

Delete resources: `terraform destroy -auto-approve`



