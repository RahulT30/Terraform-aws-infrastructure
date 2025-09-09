# Terraform-aws-infrastructure
This project provisions AWS infrastructure using Terraform.

## Resources Created
- EC2 Instance (Amazon Linux 2)
- S3 Bucket
- Security Group (SSH + HTTP)

## Usage
1. Configure AWS CLI: `aws configure`
2. Initialize: `terraform init`
3. Plan: `terraform plan`
4. Apply: `terraform apply -auto-approve`
5. Destroy: `terraform destroy -auto-approve`

## Outputs
- EC2 Public IP
- S3 Bucket Name
