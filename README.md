Role Name
=========

An Ansible role that installs Asterisk (packages) on Ubuntu servers.

[Asterisk](https://www.asterisk.org/) is a free and open source framework for building communications applications and is sponsored by [Digium](https://www.digium.com/).

Requirements
------------

This role will install a tonne of dependancies via apt-get when the asterisk package is installed. Too many to list here.

Currently only tested on 
 - Ubuntu 18.04 LTS (Bionic Beaver)

Role Variables
--------------

None. Future revisions may have variables to install optional asterisk packages such as regional sounds etc.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: pabxservers
      roles:
         - LukasGibb.asterisk

Note: This role is very basic and simply installs Asterisk. Configuration management will need to be done seperately.

License
-------

MIT

Author Information
------------------

This role was created in 2018 by [Lukas Gibb](https://github.com/LukasGibb), from [CloudJourneyman.com](http://www.cloudjourneyman.com/)
