# ansible-role-docker-install
### Sample playbook.yml file

```sh
---
- name: Install Docker on Debian based system
  hosts: all
  become: true
  roles:
    - role: ansible-role-docker-install
      docker_users:
        - ubuntu
```
