# ansible-trigger_pipelines

[![Galaxy Role](https://img.shields.io/badge/galaxy-trigger_pipelines-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/trigger_pipelines)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-trigger_pipelines.svg)](https://github.com/lotusnoir/ansible-trigger_pipelines/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-trigger_pipelines?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/trigger_pipelines)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/trigger_pipelines)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/lotusnoir/trigger_pipelines)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

## Description

Trigger gitlab pipelines.
## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: trigger_pipelines
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-trigger_pipelines


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
