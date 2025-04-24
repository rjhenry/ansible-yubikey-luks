yubikey-luks
=========

Manages [`yubikey-luks`](https://github.com/cornelinux/yubikey-luks) on a host.

Requirements
------------

At this point in time, this role is only tested on Debian machines.

Role Variables
--------------

Variables for this role are documented in
[`defaults/main.yml`](defaults/main.yml) or in [`vars/main.yml`](vars/main.yml).

Dependencies
------------

The `community.crypto.luks_device` module is required to manage enrollment of a
Yubikey to a LUKS device.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT
