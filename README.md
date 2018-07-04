Ansible role: rpi_expandfs
=========

[![MIT licensed][mit-badge]][mit-link]
[![Galaxy Role][role-badge]][galaxy-link]

Ansible role for expanding the raspberrypi file system after flushing the linux os image to sd-card.

Requirements
------------

NOTE: Role requires Fact Gathering by ansible!

One of the following OS (or deriviatives):
 - Debian jessie (Raspbian, Minibian)
 - Centos 7

The role installs *parted* and *raspi-config* packages as dependencies

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

    - hosts: rpi
      gather_facts: yes
      roles:
         - drew_kun.rpi_expandfs

License
-------

[MIT][mit-link]

Author Information
------------------

Andrew Shagayev | [e-mail](mailto:drewshg@gmail.com)

[role-badge]: https://img.shields.io/badge/role-drew__kun.rpi__expandfs-green.svg
[galaxy-link]: https://galaxy.ansible.com/drew_kun/rpi_expandfs/
[mit-badge]: https://img.shields.io/badge/license-MIT-blue.svg
[mit-link]: https://raw.githubusercontent.com/drew_kun/ansible-rpi_expandfs/master/LICENSE
