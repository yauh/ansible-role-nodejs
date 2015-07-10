# yauh.nodejs
Ansible role for setting up Node.js

## Requirements
SSH access to the remote machine

## Role Variables

```
nodejs_version: v0.10.36   # remember to use a leading v
```

## Dependencies
None

## Example Playbook

```
- hosts: all
  roles:
     - { role: yauh.nodejs }
```

## License
BSD

## Author Information
Stephan Hochhaus stephan@yauh.de

[https://github.com/yauh](https://github.com/yauh)
