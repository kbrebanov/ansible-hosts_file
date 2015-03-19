hosts_file
==========

Configures /etc/hosts file

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

1) Configure /etc/hosts file

    - hosts: all
      roles:
         - { role: hosts_file }

License
-------

BSD

Author Information
------------------

Kevin Brebanov
