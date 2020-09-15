Role Name
=========

This sole sets dockers cgroupengine to systemd and enabled userns-remap.
Remapping is done to user dockusr. User dockusr is createt without shell and password.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

Usage:

    - hosts: servers
      roles:
         - pit4shit.k8scgroup

License
-------

BSD

