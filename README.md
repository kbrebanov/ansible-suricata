suricata
========

[![Build Status](https://travis-ci.org/kbrebanov/ansible-suricata.svg?branch=master)](https://travis-ci.org/kbrebanov/ansible-suricata)

Installs suricata

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

| Name             | Default | Description                    |
|------------------|---------|--------------------------------|
| suricata_version | 3.0     | Version of suricata to install |

Dependencies
------------

None

Example Playbook
----------------

Install suricata
```
- hosts: all
  roles:
    - { role: kbrebanov.suricata }
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
