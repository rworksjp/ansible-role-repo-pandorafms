repo-pandorafms
=========

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
