andrewrothstein.sshd
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-sshd.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-sshd)

Installs the SSH server

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.sshd
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
