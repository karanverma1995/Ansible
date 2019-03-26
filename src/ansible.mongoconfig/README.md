ansible.mongoconfig
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

    - hosts: YourConfigserversGroup
      roles:
         - ansible.mongoconfig

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
