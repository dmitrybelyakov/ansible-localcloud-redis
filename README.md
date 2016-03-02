localcloud-redis
=========
This role installs redis server and redis tools on an ubuntu box.

Requirements
------------

A fresh Ubuntu 14 LTS box (trusty).

Role Variables
--------------

`redis_port` 
Listens on specified port. Defaults to 6379


`redis_bind`
Listens for connections on the interface. Defaults to 127.0.0.1


Dependencies
------------

This role has no dependencies.

Example Playbook
----------------

```yml
- hosts: servers
  roles:
     - localcloud-redis

```

License
-------

MIT License


