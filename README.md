redis.role
=========

The role installs redis server on RHEL/CentOS/Fedora.
It is based on davidwittman.redis role.

Role Variables
--------------

# whether to disable Transparent Huge pages as per redis recommendation
thp_disable: true

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - { role: redis.role }

License
-------

GPLv2

Author Information
------------------

Ilya Rubinchik, a.k.a. Citius
