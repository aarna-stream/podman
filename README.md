aarna_stream.podman
=========
![Build Status](https://github.com/andrewrothstein/ansible-podman/actions/workflows/build.yml/badge.svg)

Installs [Podman](https://podman.io/)

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
    - aarna_stream.podman
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
