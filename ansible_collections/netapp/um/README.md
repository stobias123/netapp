=============================================================

 netapp.um

 NetApp Unified Manager(AIQUM 9.7/OCUM) Collection

 Copyright (c) 2020 NetApp, Inc. All rights reserved.
 Specifications subject to change without notice.

=============================================================
# Installation
```bash
ansible-galaxy collection install netapp.um
```
To use Collection add the following to the top of your playbook, with out this you will be using Ansible 2.9 version of the module
```
collections:
  - netapp.um
```
# Need help
Join our Slack Channel at [Netapp.io](http://netapp.io/slack)

# Release Notes

## 20.5.0

### New Modules
- na_um_list_clusters: list clusters.