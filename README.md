Role Name
=========

Debian Jessie Standalone Server Base

Requirements
------------

Debian Jessie minimal installation.

Role Variables
--------------

 - jessie_server_base_mirror: http://ftp.de.debian.org/debian

Firewll settings
================

external interface:
jessie_server_base_ext_if: eth0

does it get its ip via dhcp?:
jessie_server_base_ext_if_dhcp: 0

Dependencies
------------

- working mail, e.g. mailx

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: geromueller.jessie-server-base }

License
-------

BSD

Author Information
------------------

Gero Müller <post@geromueller.de>
