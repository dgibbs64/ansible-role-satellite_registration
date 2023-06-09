# Satellite Registration

An [Ansible](https://www.ansible.com) role that registers a Server with Red Hat Satellite.

The registration command is generated in Satellite under Hosts -> Register Host. Ensure that the token lifetime is set to unlimited.
## Requirements

None.

## Role Variables

```yaml
---
satellite_registration_command:
satellite_registration_clean: true
```
## Dependencies

None.

## Example Playbook

```yaml
---
- name: Satellite Registration
  hosts: all
  roles:
    - role: "dgibbs64.satellite_registration"
```

## License

MIT

## Author Information

- [Daniel Gibbs](https://danielgibbs.co.uk)