ansible-role-k8s
=========

ansible role k8s

Requirements
------------

ubuntu 18.04

Role Variables
--------------

```
k8s_mode: "master"
k8s_mode: "worker"
k8s_mode: "teardown"
```

Dependencies
------------

None.

Example Playbook
----------------
```
   - hosts: servers
      vars:
         k8s_mode: "master"
      roles:
         - { role: redtree0.ansible-role-k8s }

```
 
License
-------

BSD

Author Information
------------------

This role was created in 2018.
