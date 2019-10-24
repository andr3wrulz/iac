# iac
Infrastructure As Code for my homelab

##Steps for running the scripts
1. Install centos
2. Install git and python ```sudo yum install git python```
3. Install ansible ```sudo yum install ansible```. For centos 8, it isn't available yet through the normal yum install so you can install it with pip ```sudo yum install python3-pip && pip install ansible --user```
4. Execute the script ```ansible-playbook [playbook] --ask-vault-pass```
