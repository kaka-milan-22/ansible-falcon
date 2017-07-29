mysql_server
========

Install mysql server.

Requirements
------------


Role Variables
--------------

```
mysql_root_user: root
mysql_root_password: mapr
```

Dependencies
------------


Example Playbook
-------------------------

```
- hosts: mysql
  roles:
    - { role: mysql-server,
        mysql_root_user: root,
        mysql_root_password: mapr }
```

License
-------

MIT

Author Information
------------------

vgonzalez@mapr.com