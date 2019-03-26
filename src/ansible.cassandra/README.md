ansible.cassandra
=========

This role installs and configures hosts for cassandraDB Cluster

------------

Role Variables
--------------

groupname = [cassandra-cluster]
main_nodes_ips in default/main.yml
In Inventory File add "ansible_ip=host_ip" in front of hostnames

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: cassandra-cluster
      roles:
         - ansible.cassandra

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
