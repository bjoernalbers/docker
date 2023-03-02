# Ansible Role: Docker

Installs Docker on Ubuntu.

## Requirements

None.

## Role Variables

### `docker_swarm`

Set `docker_swarm: yes` to initialize a Docker Swarm on the host (default: no).

## Dependencies

None.

## Example Playbook

```yaml
    - hosts: all
      roles:
         - role: bjoernalbers.docker
           docker_swarm: yes
```
