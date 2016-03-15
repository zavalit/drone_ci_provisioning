Docker Ansible role
=========

It let to get a docker setup on your machine with:
- **docker** itself
- **docker-compose** as container orchestration tool
- **docker-machine** as VM orchestration tool
- **virtualbox** as VM provider

Requirements
------------

ubuntu 14.04 and above

Role Variables
--------------

    docker_compose_version: 1.6.2
    docker_version: 1.10.2
    docker_machine_version: 0.6.0
    virtualbox_version: 5.0.14


Example Playbook
----------------

    - hosts: servers
      roles:
         - zavalit.docker

License
-------

MIT
