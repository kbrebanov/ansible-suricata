suricata
========

Installs suricata

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

| Name             | Default | Description                    |
|------------------|---------|--------------------------------|
| suricata_version | 2.0.8   | Version of suricata to install |

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
