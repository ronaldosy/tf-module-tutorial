# Terraform Module Tutorial
This repo contain simple Security Group Module.
This module will create a Security Group which Allow HTTP & HTTP Access

### Input Variable
### - sg_name
    - Name of the Security Group
    - Type: String

### - sg_description
    - Description of Security Group
    - Type: String
### - vpc_id
    - VPC ID where the security group will be created
    - Type: String
### - cidr_block: CIDR blok for ingress
    - Ingress CIDR block
    - Type: List(string)

### Output Variable:
### - sg_id
    - Security Group ID