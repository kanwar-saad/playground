Role Name: docker_host
----------------------
Ansible role to setup docker host on ubuntu 16.04.

Requirements
------------
- works only on ubuntu 16.04

Role Variables
--------------
- target_arch  -> [amd64 | armhf]

Dependencies
------------
None

Example Playbook
----------------
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
