### This playbook is intended for the first time setup of EDB on ppc64le servers

#### Install the collections
ansible-galaxy collection install edb_devops.edb_postgres --force

#### Usage of this playbook
ansible-playbook playbook.yml -i inventory
