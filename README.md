Ansible Role: osm_java
=========

An ansible role to install and configure Java.

Version History
---------------

|**Date**| **Version**| **Description**| **Changed By** |
|----------|---------|---------------|-----------------|
|**June '15** | v.1.0 | Initial Draft | Sudipt Sharma |

Salient Features
----------------
* This role will fetch and install java version 8 but if you want to install a specific veriosn you may pass it in variables.

Supported OS
------------
  * CentOS:7
  * CentOS:6
  * Ubuntu:bionic
  * Ubuntu:xenial

Role Variables
--------------
|**Date**| **Version**| **Description**|
|--|--|--|
|java_version_redhat| java-1.8.0 | Java version for Centos|
|java_version | openjdk-8-jdk | Java version for Ubuntu 

Inventory
----------
An inventory should look like this:-
```ini
[javahost]                 
192.168.1.198    ansible_user=ubuntu   
192.168.3.201    ansible_user=opstree 
```

Example Playbook
----------------
* Here is an example playbook:-
```
- hosts: javahost
  roles:
    - role: osm_java
```
References
----------
- **[software](https://www.java.com/en/)**

Author Information
------------------

- Tejasvi Rana
- tejasvi.rana@opstree.com