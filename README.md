# Ansible Role: firewalld

An Ansible role that installs firewalld on Fedora and configures the default zone.

By default the ssh port is open in the public zone, this role will close that.

## Requirements

None

## Role Variables

Available variables are listed below, along with default values:

    firewalld_default_zone: public

## Dependencies

None

## Example Playbook

    - hosts: all
      roles:
        - { role: mjanser.firewalld }

## License

MIT
