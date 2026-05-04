Adding the Terraform Project
https://github.com/taruch/ansible-terraform.git

Create a Terraform Setup Job Template



# ansible-terraform

You can update the 'Terraform State Credential' Backend configuration
field with the below information after updating the AWS credential
information (access_key / secret key). -->


## When you want to use this in AAP
bucket = "aap-tf-bucket-5abacb29-72ff-48ac-afeb-ec4f3cf6f0d7"
key = "ec2-instance/terraform.tfstate"
region = "us-east-2"
access_key = "<changeme>"
secret_key = "<changeme>"

Run the 'TERRAFORM / Create S3 Bucket for State File' Job Template to create the bucket