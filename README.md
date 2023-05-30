# ansible-system_apt_sources

[![Galaxy Role](https://img.shields.io/badge/galaxy-system_apt_sources-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/system_apt_sources)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-system_apt_sources.svg)](https://github.com/lotusnoir/ansible-system_apt_sources/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-system_apt_sources?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/system_apt_sources)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/system_apt_sources)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/lotusnoir/system_apt_sources)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

## Description

Configures /etc/apt/sources.list
## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

With default variables, this role keep original settings. You need to set the config variables like in the exemple in order to start configuration.

## Examples

        ---
        - hosts: system_apt_sources
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-system_apt_sources
          vars:
            apt_sources_debian_components:
              - main
              - contrib
              - non-free
            apt_sources_enable_backports: true
            apt_sources_enable_proposed: false
            apt_sources_enable_security: true
            apt_sources_enable_updates: true



## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
