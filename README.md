# clc12-network

## Instalar Terraform

https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli

=====

https://developer.hashicorp.com/terraform/install#linux

sudo yum install -y yum-utils
sudo yum-config-manager --add-repo https://rpm.releases.hashicorp.com/AmazonLinux/hashicorp.repo

sudo yum -y install terraform

=====

Gerar par de chaves ssh para adicionar no repositório:
ssh-keygen

cat /home/ec2-user/.ssh/id_rsa.pub
