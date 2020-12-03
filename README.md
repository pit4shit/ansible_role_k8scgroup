Role Name
=========

This sole sets dockers cgroupengine to systemd.

Requirements
------------

None

Role Variables
--------------

http_proxy  ip or hostname and Port of Proxy
no_proxy  ips or hosts where no proxy is to be used


Dependencies
------------

None

Example Playbook
----------------

Usage:

    - hosts: servers
      vars:
         - http_proxy: 'myproxy:3128'
         - no_proxy: '127.0.0.1,192.168.0.1'

      roles:
         - pit4shit.k8scgroup

License
-------

BSD
