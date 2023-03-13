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
        - role: locales
          locale_gen:
            - en_US.UTF-8
            - fr_FR.UTF-8
          locale_default:
            LANG: en_US.UTF-8
            LANGUAGE: en_US:en
            LC_MEASUREMENT: fr_FR.UTF-8
            LC_MONETARY: fr_FR.UTF-8
            LC_NUMERIC: fr_FR.UTF-8
            LC_PAPER: fr_FR.UTF-8
            LC_TIME: fr_FR.UTF-8

## License

GPLv3

## Author Information

http://www.sekoya.org
