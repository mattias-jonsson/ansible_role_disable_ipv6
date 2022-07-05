Ansible Role: ansible_role_disable_ipv6
=========

An Ansible role that through sysctl disabled IPv6 repositories on supported distributions.

<ul>
<li>Debian
<li>Enterprise Linux
</ul>

Requirements
------------

This role has no dependencies besides what is included in Ansible Core.

Role Variables
--------------

This role has no user configurable variables.


Dependencies
------------

This role has no external dependencies.

Example Playbook
----------------

    - hosts: servers

      roles:
         - role: ansible_role_disable_ipv6

License
-------

MIT

Author Information
------------------

Mattias Jonsson
