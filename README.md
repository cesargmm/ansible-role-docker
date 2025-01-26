# ansible-role-docker

## Description

This Ansible role installs and sets up Docker on Linux systems.

> [!NOTE]
> By installing this rile sudo users will also be added to docker group.

## Requirements

* Ansible 2.14.16 or later
* Linux distribution (Debian, Ubuntu, CentOS, Fedora, Raspbian, etc)

## Playbook Example

Here's a playbook example of how to use this role:

```yaml
---
- hosts: localhost
  become: true
  roles:
    - ansible-role-docker
```
