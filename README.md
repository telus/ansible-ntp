# ansible-ntp

[NTP](https://help.ubuntu.com/lts/serverguide/NTP.html) is a TCP/IP protocol for synchronising time over a network.

[![Build Status](https://travis-ci.org/telusdigital/ansible-ntp.svg?branch=travis)](https://travis-ci.org/telusdigital/ansible-ntp)
[![Platforms](http://img.shields.io/badge/platforms-ubuntu-lightgrey.svg?style=flat)](#)

Tunables
--------
* `ntp_timezone` (string) - 

Dependencies
------------
None.

Example Playbook
----------------
    - hosts: servers
      roles:
         - role: telusdigital.ntp

License
-------
[MIT](https://tldrlegal.com/license/mit-license)

Contributors
------------
* Ben Visser
