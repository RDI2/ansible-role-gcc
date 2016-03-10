Ansible Role - gcc
==================

This playbook installs gcc

Platforms
---------

CentOS 6.7 is the only platform that is supported and tested so far.

Role Variables
--------------

- Check out [defaults/main.yml](defaults/main.yml)

Dependencies
------------

None.

Installation
------------

Regular installation:

```
ansible-galaxy install RDI2.gcc
```

Installation to a specific directory(e.g. roles/):

```
ansible-galaxy install -p roles/ RDI2.gcc
```

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: RDI2.gcc }

License
-------

MIT License.

Author Information
------------------

- Koji Tanaka, RDI2
