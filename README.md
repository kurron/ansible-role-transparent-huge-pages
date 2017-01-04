Role Name
=========

Disabling of Transparent Huge Pages (THP), initially targetted to RHEL.  Database
workloads do not do well with THP enabled.

Requirements
------------

TODO

Role Variables
--------------

None.

Dependencies
------------

* kurron.base

Example Playbook
----------------

```
- hosts: servers
  roles:
      - { role: kurron.transparent-huge-pages }
```

License
-------

This project is licensed under the [Apache License Version 2.0, January 2004](http://www.apache.org/licenses/).

Author Information
------------------

[Author's website](http://jvmguy.com/).
