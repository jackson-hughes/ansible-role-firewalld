[![Build Status](https://travis-ci.org/jhughes01/ansible-role-firewalld.svg?branch=master)](https://travis-ci.org/jhughes01/ansible-role-firewalld)

Ansible role: Firewalld
=========

This role installs and configures firewalld.

Requirements
------------

Python2 firewalld libs if python2 is not present on system.

Role Variables
--------------

This role supports two variable lists:

`firewalld_active_services`: A list of firewall services to be enabled.
`firewalld_open_ports`: A list of ports (and protocols) to be opened by firewalld.

Dependencies
------------

This role has no dependencies.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-firewalld }

License
-------

GNU GPL v3
