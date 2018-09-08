Role Name
=========

Based on OpenSSL PKI tutorial
https://pki-tutorial.readthedocs.io/en/latest/index.html#

This implements the OPenSSL PKI Tutorial's "simple PKI" as an Ansible role. It handle:
- the Root CA and signing CA creation,
- the server cert creation.

Requirements
------------

The PKI environment is installed ont the Ansible controller itself. as a consequence, the role will install openSSL and python's openssl libs on the host acting as Ansible controller

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT

Author Information
------------------

[*Eric Belhomme*](https://github.com/eric-belhomme), initiator and maintainer for this *Ansible role*
