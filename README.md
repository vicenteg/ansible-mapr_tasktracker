mapr-tasktracker
========

Install mapr-tasktracker.

Requirements
------------


Role Variables
--------------

```
proxy_env:
  http_proxy: http://1.2.3.4:3128
  https_proxy: https://1.2.3.4:3128
```

Dependencies
------------

Example Playbook
-------------------------

```
- hosts: tasktracker
  roles:
    - mapr-tasktracker
```

License
-------

MIT

Author Information
------------------

vgonzalez@mapr.com