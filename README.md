Ansible Role - Sass Scsslint
============================

A sass scsslint role to install sass scsslint on elao symfony standard vagrant box

Requirements
------------

This role only run on elao symfony standard vagrant box. See https://vagrantcloud.com/elao/symfony-standard-debian

Role Variables
--------------

* version: (optionnal) Scsslint version

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: elao.sass-scsslint }

License
-------

MIT

Author Information
------------------

http://www.elao.com/
