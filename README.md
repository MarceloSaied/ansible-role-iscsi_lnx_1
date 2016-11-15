# README.md
# ansible-role-iscsi_lnx_1
Ansible iscasi configuration for Linux CentOS


# Ansible Role: ISCSI NETAPP LNX 0.1
An Ansible role that installs ISCSI to NETAPP on Centos 6.x


## Requirements

NETAPP iqn configuration done

## Role Variables

Available variables are listed below, along with default values:


## Dependencies

- username.iptables - configure the firewall off or block all ports except those needed for the netapp 3260 and ssh access.
- username.common - perform common server base configuration

## Example Playbook

    - hosts: webservers
      roles:
        - { role: username.role }

## License

MIT
