ansible.mongorouter
=========

This Role Installs And Configures Mongo DB Query Router In MongoDB Cluster

Requirements
------------
Ansible 2.7

Role Variables
--------------

mongodb_port
ansible_ip=hostip in front of every host in inventory file 


Example Playbook
----------------

    - hosts: routerservers
      roles:
         - ansible.mongorouter




