Mongodb Ansible role
=========

This role installs and configures Mongodb on Ubuntu/Debian system using
either Mongo-native packages or from given distribution. This role is based
on /Stouts.Mongodb/ role from Galaxy.

Requirements
------------

Ubuntu at least from Xenial release or Debian stretch/jessie.
To test the role on various distribution install [Molecule framework](https://github.com/metacloud/molecule)

Role Variables
--------------



Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: mongodb, mongodb_version: 3.6 }

License
-------

BSD
