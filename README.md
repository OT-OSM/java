Role Name: osm_java
=========

Installs Java for RedHat/CentOS and Debian/Ubuntu linux servers.

Requirements
------------

Python 2.7* (to run ansible)

Role Variables
--------------
java_version: java-1.8.0

Dependencies
-------------
None.

Example Playbook
----------------

---
- hosts: host
  roles:
    - role: osm_java