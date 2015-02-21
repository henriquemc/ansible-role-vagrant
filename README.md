henrique.vagrant
=========

An Ansible role for installing Vagrant.

Requirements
------------

This role requires Ansible 1.4 or higher and platform requirements are listed in the metadata file.

Role Variables
--------------

Some variables are listed below, along with default values (see vars/main.yml):

    vagrant_version: "latest" # Use "latest" for use last release
    vagrant_arch: "x86_64" # Set arch: "x86_64" or "i686"

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

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
