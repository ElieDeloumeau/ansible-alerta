Alerta
=========

[![Build Status](https://travis-ci.org/googley/ansible-alerta.svg?branch=master)](https://travis-ci.org/googley/ansible-alerta)

This role installs Alerta server, client and UI.

Install
-------

```shell
ansible-galaxy install googley.alerta
```

Requirements
------------

* Ansible 2.2
* Debian 7/8 or Ubuntu 14.04 and higher

### 

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
         - googley.alerta

Dependencies
------------

* geerlingguy.apache

License
-------

MIT

Author Information
------------------

[Élie Deloumeau-Prigent](https://googley.fr/), System engineer.
