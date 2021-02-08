# local-yum-redhat
This playbook is created to configure yum repository locally on RHEL8 VM.

# Ansible playbook
This ansible playbook can configure local yum repository using mounted RHEL DVD on your RHEL8 virtual machine.
This playbook also installs epel repository for extra packages which is not provided by DVD and it also installs sshpass package which is required for ansible to connect remote target node using ssh protocol.

# How to run this playbook?
First, make sure to install ansible on your system using the following command.\
`pip3 install ansible`\
Then clone or download this repository and run playbook using the following command.\
`ansible-playbook create_yum_repo.yml`
