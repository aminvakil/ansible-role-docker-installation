Role Name
=========

Ansible Docker Installation

Requirements
------------

None.

Role Variables
--------------

`docker_compose` which is a boolean you can change it true or false if you want docker compose to be installed.

`docker_compose_version` which currently is the latest version (1.27.4).

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      become: true
      roles:
         - role: aminvakil.docker_installation

License
-------

MIT

Author Information
------------------

[Amin Vakil](https://www.aminvakil.com/)
