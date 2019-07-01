# Ansible user setup Playbook
 
This playbook is for setting up your user for passwordless authentication to a remote server. 

## Notes and requirements

 - The playbook was built and tested on Ubuntu 18.04 VMs 
 - You will need Ansible installed and running
 
## Instructions
 
 1. Have an existing public/private key pair generated.
 2. Run this playbook with:
 `ansible-playbook -K site.yml`
