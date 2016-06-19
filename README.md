Ansible role - Update mail aliases
=====
[![Build Status](https://travis-ci.org/repleo/ansible-role-aliases.svg?branch=master)](https://travis-ci.org/repleo/ansible-role-aliases)
[![Ansible Galaxy](http://img.shields.io/badge/galaxy-repleo.aliases-660198.svg?style=flat)](https://galaxy.ansible.com/repleo/aliases)


update mail aliases database

Role Variables
--------------

- `aliases`

Example Playbook
-------------------------

    - hosts: servers
      roles:
         - { role: repleo.aliases,
             aliases:
               - { user: root, alias: jeroen, staff }
               - { user: info, alias: jeroen, sales }

License
-------

BSD - (c) 2016, Repleo, Amstelveen

Author Information
------------------

Repleo, Amstelveen, Holland -- www.repleo.nl
Jeroen Arnoldus (jeroen@repleo.nl)

Original by: Tsuyoshi Maekawa (https://github.com/xcezx)