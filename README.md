Role Name: osm_java
=========

Installs Java for RedHat/CentOS and Debian/Ubuntu linux servers.

Requirements
------------

Python 2.7* (to run ansible)

Role Variables
--------------
java_version
for ubuntu 14/16 : oracle-java8-installer
for CentOS 7/8 : java-1.8.0 and java-1.7.0

Dependencies
-------------
None.

Example Playbook
----------------

---
- hosts: host
  roles:
    - role: osm_java
