###### Check docker is running 
- ssh instance 
- docker ps

###### Test port
- Public-IPv4-address:8080/


###### terraform.tfvars file example 
```terraform
vpc_cidr_block      = "10.0.0.0/16"
subnet_cidr_block   = "10.0.10.0/24"
avail_zone          = "us-east-1a"
env_prefix          = "dev"
my_ip               = "********"
instance_type       = "t2.micro"
public_key_location = "/Users/bakarydiallo/.ssh/id_rsa.pub"
image_name          = "amzn2-ami-hvm-*-x86_64-gp2"
```
# aws-ec2-docker-nginx-terraform-modules
