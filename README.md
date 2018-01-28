Ansible role: rpi_expandfs
=========

[![MIT licensed][mit-badge]][mit-link]
[![Galaxy Role][role-badge]][galaxy-link]

Ansible role for expanding the raspberrypi file system after flushing the linux os image to sd-card.

Requirements
------------

One of the following OS (or deriviatives):
 - Debian (jessie)
 - Raspbian
 - Minibian

The role installs *parted* and *raspi-config* packages as dependencies

Role Variables
--------------

No variables set.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: rpi
      roles:
         - drewshg312.rpi_expandfs

License
-------

[MIT][mit-link]

Author Information
------------------

Andrew Shagayev

[role-badge]: https://img.shields.io/badge/role-drew--kun.rpi__expandfs-green.svg
[galaxy-link]: https://galaxy.ansible.com/drew-kun/rpi_expandfs/
[mit-badge]: https://img.shields.io/badge/license-MIT-blue.svg
[mit-link]: https://raw.githubusercontent.com/drew-kun/ansible-rpi_expandfs/master/LICENSE
