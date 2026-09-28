# abc-ansible

This repository contains a basic Ansible project scaffold for environment-specific deployments.

## Structure
- inventories/: environment inventories and variables
- playbooks/: reusable playbooks for site, deploy, patch, and health checks
- roles/: shared role directories for application and infrastructure tasks
- collections/: collection dependencies

## Getting started
1. Review the inventory files under `inventories/`.
2. Install dependencies with `ansible-galaxy install -r requirements.yml`.
3. Run a playbook such as `ansible-playbook playbooks/site.yml`.



## Creating Project on Ansible AWX for the 

> Organization > ADD > Name:ABC-PROJECT
# Create project
## Creating the Teams in the Ansible AWX
> TEAMS
 ↓
ABC-PROJECT
 ↓
 ABC-ADMIN
ABC-DEVELOPERS
ABC-OPERATIONS
ABC-READONLY

## Create Users and Add to teams
xyz-admin  (password)
abc-developers 
abc-operations 
 ## we can used user.cvs using python script or LDAP

 # # Create Credentials
 Resources
 ↓
Credentials
 ↓
Add
Git Credentials & machine Credentials Create
