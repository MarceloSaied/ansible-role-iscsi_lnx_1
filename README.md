# README.md
# ansible-role-iscsi_lnx_1
Ansible iscsi configuration for Linux Centos 6.x

Role Name
=========

ISCSI NETAPP LNX 0.1
An Ansible role that installs ISCSI to NETAPP on Centos 6.x

Requirements
------------

iqn configuration done at NETAPP 

Role Variables
--------------

Available variables are listed below, along with default values:


Dependencies
------------

- username.iptables - configure the firewall off or block all ports except those needed for the netapp 3260 and ssh access.
- username.common - perform common server base configuration


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT

Author Information
------------------



