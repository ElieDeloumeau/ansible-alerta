Alerta
=========

[![Build Status](https://travis-ci.org/googley/ansible-alerta.svg?branch=master)](https://travis-ci.org/googley/ansible-alerta)

This role installs Alerta server, client and UI.

Requirements
------------

* Ansible 2.2

You need to install requirements :

`ansible-galaxy install -r requirements.yml`

Role Variables
--------------
*TO DO*

* oauth_client_id
* oauth_client_secret
* gitlab_auth
* gitlab_url

Example Playbook
----------------

    - hosts: servers
      roles:
         - ansible-alerta

Dependencies
------------

* geerlingguy.apache

License
-------

MIT

Author Information
------------------

[Élie Deloumeau-Prigent](https://googley.fr/), System engineer.
