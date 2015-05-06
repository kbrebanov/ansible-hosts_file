hosts_file
==========

[![Ansible Galaxy](https://img.shields.io/badge/galaxy-kbrebanov.hosts_file-660198.svg)](https://galaxy.ansible.com/list#/roles/3387)

Configures /etc/hosts file

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

| Name                      | Default                  | Description    |
|---------------------------|--------------------------|----------------|
| hosts_file_local_fqdn     | "{{ ansible_fqdn }}"     | Local FQDN     |
| hosts_file_local_hostname | "{{ ansible_hostname }}" | Local hostname |

Dependencies
------------

None

Example Playbook
----------------

Configure /etc/hosts file using default values
```
- hosts: all
  roles:
    - { role: kbrebanov.hosts_file }
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
