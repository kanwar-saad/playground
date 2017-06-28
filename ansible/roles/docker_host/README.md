Role Name
=========

Ansible role to setup docker host on ubuntu 16.04.

Requirements
------------
- works only on ubuntu 16.04

Role Variables
--------------
- target_arch  -> [amd64 | armhf]

Dependencies
------------

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      become: true
      roles:
         - { role: ../roles/docker_host, target_arch: "amd64" }

License
-------

BSD

Author Information
------------------
 Kanwar
