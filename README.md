ansible_role_docker
=========

An Ansible role to install Docker in Debian or Ubuntu.

https://docs.docker.com/engine/installation/linux/debian/

Requirements
------------

64bit Debian / Ubuntu

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: lexrus.docker }

License
-------

BSD

Author Information
------------------

[Lex Tang](http://lexrus.com)([@lexrus](https://twitter.com/lexrus))
