# Ansible Role: firewalld

An Ansible role that installs and configures the default zone firewalld.

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
