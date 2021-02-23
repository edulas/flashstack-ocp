ci-ontap_roles
=============
The ci-ontap-roles repository contains all the Ansible roles to setup NetApp ONTAP storage components for a FlexPod reference architecture.

Example Playbook
----------------
```YAML
---
- hosts: ontap
  connection: local


  vars:
    TBD: abc


  roles:
    - ontap_primary_setup
```

