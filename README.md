# ansible-smartd
An Ansible role to install smartmontools on CentOS / Fedora systems.

You just need to replace the variable in var/main.yml with your email.

# Example Playbook

```
---
- hosts: test
  remote_user: root
  roles: 
    - role: ansible-smartd
```
