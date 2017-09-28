repo-pandorafms
=========

[![Travis](https://travis-ci.org/rworksjp/ansible-role-repo-pandorafms.svg?branch=master)](https://travis-ci.org/rworksjp/ansible-role-repo-pandorafms)
[![Ansible Role](https://img.shields.io/ansible/role/14693.svg)](https://galaxy.ansible.com/rworksjp/repo-pandorafms/)

Ansible role to add [Pandora FMS](https://pandorafms.org/) official repository.

Requirements
------------

None.

Role Variables
--------------

Availabe role variables are listed below, along with default values:

```yaml
repo_pandorafms_enabled: yes
```

`repo_pandorafms_enabled` is a variable to specify enable/disable Pandora FMS repo by default.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - rworks.repo-pandorafms

License
-------

BSD
