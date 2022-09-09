Ansible server setup automating
=========

Simple Ansible playbook to prepare your Linux server for work

Requirements
------------

- Ansible 2.7 or higher
- Linux server

Role Variables
--------------

- `create_user` # user to be created on machine with sudo priveleges
- `system_packages` # name of sys.packages to be installed on your machine while playbook executing
