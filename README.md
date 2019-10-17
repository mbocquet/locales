# locales

Ansible role to configure locales.

## Requirements

None.

## Role Variables

See defaults/main.yml.

## Dependencies

None.

## Install this role as submodule in a git repository

`git submodule add https://git.sekoya.org/mb/locales.git roles/locales`

## Example Playbook

    - hosts: servers
      roles:
         - locales
or

    - hosts: servers
      roles:
         - { role: locales, locales_default: 'en_US.UTF-8' }

## License

GPLv3

## Author Information

http://www.sekoya.org
