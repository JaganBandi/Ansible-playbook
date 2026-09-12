# Linux User Management Using Ansible

## Overview
This project automates Linux user and group management on multiple servers using Ansible.

## Tools
- Ansible
- YAML
- Rocky Linux

## Tasks Automated
- Created DevOps group
- Created multiple users
- Created user home directories
- Used variables and loops
- Configured sudo access
- Verified users and permissions

## Run Playbook

Using Commands:

1. vim --> For edit the file 
2. ansible-playbook -i inventory.ini user-security --syntax-check --> for Checking the playbook syntax
3. ansible-playbook -i inventory.ini user-security.yml --> Run the ansible ansible playbook
