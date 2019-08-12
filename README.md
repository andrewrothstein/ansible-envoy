andrewrothstein.envoy
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-envoy.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-envoy)

Installs [Envoy](https://www.getenvoy.io)

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
    - andrewrothstein.envoy
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
