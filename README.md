rpi_expandfs
=========

Ansible role for expanding the raspberrypi file system after flushing the linux os image to sd-card.

Requirements
------------

The role installs parted and raspi-config packages as dependencies

Role Variables
--------------
No variables set.

Dependencies
------------

Does not depend on other roles.

Example Playbook
----------------

    - hosts: servers
      roles:
         - rpi_expandfs

License
-------

MIT

Author Information
------------------

Andrew Shagayev
