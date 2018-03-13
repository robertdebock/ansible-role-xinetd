xinetd
=========

[![Build Status](https://travis-ci.org/robertdebock/ansible-role-xinetd.svg?branch=master)](https://travis-ci.org/robertdebock/ansible-role-xinetd)

Provides xinetd for your system.

Context
--------
This role is a part of many compatible roles. Have a look at [the documentation of these roles](https://robertdebock.nl/) for further information.

Requirements
------------

Access to a repository containing packages, likely on the internet.

Role Variables
--------------

None known.

Dependencies
------------

You can prepare your system by using this role:

- robertdebock.bootstrap

Download the dependencies by issuing this command:
```
ansible-galaxy install --role-file requirements.yml
```

Example Playbook
----------------

```
- hosts: servers

  roles:
    - role: robertdebock.bootstrap
    - role: robertdebock.xinetd

```

Install this role using `galaxy install robertdebock.xinetd`.

License
-------

Apache License, Version 2.0

Author Information
------------------

Robert de Bock <robert@meinit.nl>
