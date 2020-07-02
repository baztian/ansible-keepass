keepass ansible role
====================

![CI](https://github.com/baztian/ansible-keepass/workflows/CI/badge.svg)

Role to download, install and setup keepass.

Execute directly from the command line
--------------------------------------

    ansible-galaxy install baztian.keepass
    ansible localhost -m include_role -a 'name=baztian.keepass' -K -b

Example Playbook
----------------

    - hosts: servers
      become: yes
      roles:
         - role: baztian.keepass

License
-------

MIT
