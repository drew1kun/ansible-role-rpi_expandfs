rpi_expandfs
=========

Ansible role for expanding the raspberrypi file system after flushing the linux os image to sd-card.

Requirements
------------

One of the following OS (or deriviatives):
 - Debian
 - Raspbian
 - Minibian

The role installs parted and raspi-config packages as dependencies

Role Variables
--------------

No variables set.

Dependencies
------------

Does not depend on other roles.

Example Playbook
----------------

    - hosts: rpi
      roles:
         - drewshg312.rpi_expandfs

License
-------

MIT

Author Information
------------------

Andrew Shagayev
