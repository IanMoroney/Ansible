# Ansible user setup Playbook
 
This playbook is for setting up your user for passwordless authentication to a remote server. 

## Notes and requirements

 - The playbook was built and tested on Ubuntu 18.04 VMs 
 - You will need Ansible installed and running
 
## Instructions
 
 1. Have an existing public/private key pair generated.
 2. Ensure your /etc/ansible/hosts matches the `hosts` entry in site.yml
 3. Run this playbook with:
 `ansible-playbook -K --ask-pass site.yml`
 4. Provide the password for the user you are ssh'ing as, and the sudo password if different.
