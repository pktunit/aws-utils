# aws-utils
Collection of scripts for working with aws

aws-allow-ssh
  Uses the aws-cli to update your security groups to allow SSH ingress from your current ipv4 address on port 22.

aws-deny-ssh
  Uses the aws-cli to update your security groups and revokes all ingress rules allowing SSH access on port 22.
  
aws-update
  Uses the ansible to run Yum Update, update SSL certs using Certbot, and restart Nginx.
