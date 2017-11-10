xinetd
=========

Provides xinetd.

Requirements
------------

Access to a repository that provides the xinetd package.

Role Variables
--------------

None known.

Dependencies
------------

- robertdebock.bootstrap

Example Playbook
----------------

```
- hosts: servers
  roles:
    - robertdebock.xinetd
```

License
-------

Apache License, Version 2.0

Author Information
------------------

Robert de Bock <robert@meinit.nl>
