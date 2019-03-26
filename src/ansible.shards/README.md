ansible.shards
=========

This Role installs and configures mongo config servers in MongoDB Cluster

Requirements
------------
Ansible 2.7

Role Variables
--------------

mongodb_port
ansible_ip=hostmachineip in Inventory File as hostvariable


Example Playbook
----------------

    - hosts: YourShardserversGroup
      roles:
         - ansible.shards

