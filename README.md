# Ansible project to create and manage docker containers(acting as VMs)
Steps to reproduce-
- Create a conda env
- run command "ansible-galaxy collection install community.docker"
- run command "ansible-playbook -i inventory.ini docker-setup.yml"
