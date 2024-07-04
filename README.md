# Ansible Role: Docker

Installs Docker on Ubuntu.

## Requirements

None.

## Role Variables

### `docker_swarm`

Set `docker_swarm: true` to initialize a Docker Swarm on the host (default: `false`).

## Dependencies

None.

## Example Playbook

```yaml
    - hosts: all
      roles:
         - role: bjoernalbers.docker
           docker_swarm: true
```
