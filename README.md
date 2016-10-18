Ansible Role: Vagrant
=====================

Customizations for Vagrant development boxes.

Role Variables
--------------

 * vagrant_timezone
 * vagrant_systemd_journal_group

Requirements
------------

The following roles are required:

*  [facts](https://github.com/idi-ops/ansible-facts/)

Example Playbook
----------------

    - hosts: localhost
      roles:
         - vagrant

License
-------

MIT

Author Information
------------------

Giovanni Tirloni
