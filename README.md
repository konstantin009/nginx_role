nginx_role
=========

Ansible role for installing Nginx and configuring it like load-balancer

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

This role use role for installing and configuring Docker: konstantin009.docker_role

Example Playbook
----------------

    - hosts: all
      roles:
         - role: nginx_role

License
-------

BSD
