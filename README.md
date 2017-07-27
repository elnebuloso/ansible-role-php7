# Ansible Role - PHP 7 for Linux Server

[![Build Status](https://travis-ci.org/elnebuloso/ansible-role-php7.svg?branch=master)](https://travis-ci.org/elnebuloso/ansible-role-php7)

PHP 7 for Linux Server.

- replaces elnebuloso/ansible-role-php70
- replaces elnebuloso/ansible-role-php71
- php version is configurable

## Requirements

This role requires Ansible 2.0 or higher, and platform requirements are listed in the metadata file.

## Supported Distributions

- ubuntu16

## Role Variables

- [`defaults/main.yml`](https://github.com/elnebuloso/ansible-role-php7/blob/master/defaults/main.yml)
- [`vars/main.yml`](https://github.com/elnebuloso/ansible-role-php7/blob/master/vars/main.yml)
- [`vars/ubuntu16.yml`](https://github.com/elnebuloso/ansible-role-php7/blob/master/vars/ubuntu16.yml)
- Variables prefixed with __ (2 Underscores) are Defaults, overwrite them by writing without the Underscores

## Example Playbook

```
- hosts: localhost
  roles:
    - role: elnebuloso.php7
```

## Dependencies

None.

##  License

MIT

##  Author Information

This role was created in 2017 by [elnebuloso](https://github.com/elnebuloso/)