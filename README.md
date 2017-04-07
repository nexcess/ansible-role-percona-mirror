# Ansible Role: Percona Mirror

Installs the Percona mirroring role

## Requirements

None.

## Role Variables

See `defaults/main.yml`.

## Dependencies

nexcess.mirror

## Add to Requirements

    - src: https://github.com/nexcess/ansible-role-percona-mirror.git
      name: nexcess.percona-mirror

## Example Playbook

    - hosts: servers
      roles:
        - nexcess.percona-mirror

## License

MIT / BSD
