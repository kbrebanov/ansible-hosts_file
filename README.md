hosts_file
==========

[![Build Status](https://travis-ci.org/kbrebanov/ansible-hosts_file.svg?branch=master)](https://travis-ci.org/kbrebanov/ansible-hosts_file)

Configures /etc/hosts file

Requirements
------------

This role requires Ansible 1.9 or higher.

Role Variables
--------------

| Name                      | Default                  | Description    |
|:--------------------------|:-------------------------|:---------------|
| hosts_file_local_fqdn     | "{{ ansible_fqdn }}"     | Local FQDN     |
| hosts_file_local_hostname | "{{ ansible_hostname }}" | Local hostname |

Dependencies
------------

None

Example Playbook
----------------

Configure /etc/hosts file using default values
```yaml
- hosts: all
  roles:
    - kbrebanov.hosts_file
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
