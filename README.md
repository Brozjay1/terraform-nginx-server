PROJECT OVERVIEW
- Goal: Deploy a web server (e.g., Nginx) on AWS using Terraform, and make it accessible via the internet.
- Tools: Terraform, AWS.
- Outcome: you’ll have a fully functional web server running on AWS.

PREREQUISITES
- AWS Account: You'll need AWS access keys for authentication.
- Terraform Installed: Ensure Terraform is installed on your local machine.

STEPS
- Set Up the Directory
- Create the AWS Configuration by creating an EC2 instance and installing Nginx.
- Create the "main.tf" File to define the AWS provider and resources.
- Initialize and Apply the Configuration file by running the commands "terraform init" "terraform plan" "terraform apply"
- Terraform will output the public IP address of the AWS EC2 instanceS, then you can visit this IP in your browser to see the Nginx welcome page.
