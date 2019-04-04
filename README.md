egeneralov.zabbix-repository
============================

Provision zabbix repository installation

Requirements
------------

Any debian-based system

Role Variables
--------------

- **zbx_version** default: 4.2

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: egeneralov.zabbix-repository, zbx_version: "4.2" }

License
-------

MIT

Author Information
------------------

Eduard Generalov <eduard@generalov.net>
