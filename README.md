# amazonlinux2023_docker

Installs Docker and optional docker-compose on Amazon Linux 2023.

## Example playbook

```yaml
- hosts: all
  become: yes
  roles:
    - amazonlinux2023_docker

