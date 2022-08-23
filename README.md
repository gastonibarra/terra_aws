# Small VPC in AWS

## Description

Infrastructure as a Code using Terraform, to deploy a simple VPC in
South America, Sao Paulo.
In this VPC I have a security group with Inbound/Outbound rules.
In the other hand, there is a EC2 running Ubuntu

## Configuration

### Vars

ssh_key_path="path to public ssh key"
vpc_id="VPC value in AWS"

## Deployment

```bash

terraform init
terraform plan
terraform apply
terraform destroy
```
