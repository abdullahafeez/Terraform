###Terraform import
terraform state list

the command used to create ssh key
aws ec2 create-key-pair --endpoint http://aws:4566 --key-name jade --query 'KeyMaterial' --output text > /root/terraform-projects/project-jade/jade.pem


aws ec2 describe-instances  --endpoint http://aws:4566 

after creating the empty resource block import the resource into terraform
terraform import aws_instance.jade-mw id-of-the-resource