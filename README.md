# Ansible Role: motd

[![Build Status](https://img.shields.io/travis/mipsou/ansible.motd.svg?branch=master&style=popout-square)](https://travis-ci.org/mipsou/ansible.motd) [![license](https://img.shields.io/github/license/mashape/apistatus.svg?style=popout-square)](https://sbaerlo.ch/licence) [![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-motd-blue.svg?style=popout-square)](https://galaxy.ansible.com/mipsou/ansible_motd) [![Ansible Role](https://img.shields.io/ansible/role/d/21815.svg?style=popout-square)](https://galaxy.ansible.com/mipsou/motd)

## Description

Configure a dynamic motd file on Debian and Redhat like.

## Installation

```bash
 ansible-galaxy install mipsou.ansible_motd
```

## Requirements

None

## Example Motd

Common

## Dependencies

None

## Example Playbook

```yml
- hosts: all
  roles:
    - mipsou.ansible_motd
```

## Author

- [Simon Bärlocher](https://sbaerlocher.ch)

## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2020, Simon Bärlocher
