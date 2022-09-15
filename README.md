Role Lighthouse
=========

Lighthouse installation

Requirements
------------

target os: centos 8  
ansible-core 2.13.3

Role Variables
--------------

lighthouse_repo: lighthouse https repository from git
lighthouse_home: lighthouse installation directory

Example Playbook
----------------


    - hosts: servers
      roles:
         - lighthouse-role

License
-------

MIT

