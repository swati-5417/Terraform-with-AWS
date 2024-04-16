# Terraform-with-AWS
AWS Infrastructure creation using Terraform

Steps:
1. you need to have a terminal or linux instance with proper configuration ( here t2.medium was used for this project).
2. AWS CLI should be installed on instance created above.
3. Terraform should be insyalled on instance.
4. we need to login aws using secret access key in instance.
5. Now we need to access EC2 instance from VS code via remote connection
6. Then files like main.tf, provider.tf, and variable.tf are created as per the project requirement.
7. Then using terraform validate and terraform apply cmd the resources arec created.

The files attached in repository have below uses :

main.tf: Think of main.tf as the blueprint for your AWS infrastructure. It's where you list all the things you want to create, like servers, S3 buckets, and networks(VPC). 

provider.tf: This file tells Terraform which cloud provider you're using, like AWS, Google Cloud, or Azure.

variable.tf: Variables are like placeholders for values that might change, such as the number of servers you want or the name of your project. variable.tf is where you define these placeholders. It's like storing the variables with values and these can be used in main.tf file.

Userdata.sh : this file contain code to be executed within the instance when it is installed.
