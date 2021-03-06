# Ansible Role: composer

[![Build Status](https://travis-ci.org/sbaerlocher/ansible.composer.svg?branch=master)](https://travis-ci.org/sbaerlocher/ansible.composer) [![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://sbaerlo.ch/licence) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-composer-blue.svg)](https://galaxy.ansible.com/sbaerlocher/composer)

## Description

Installs then composer.

## Installation

```bash
ansible-galaxy install sbaerlocher.composer
```

## Requirements

None

## Role Variables

| Variable             | Default     | Comments (type)                                   |
| :---                 | :---        | :---                                              |
| composer_bin | /usr/local/bin/composer | |

## Dependencies

None

## Example Playbook

```yml
- hosts: all
  roles:
     - sbaerlocher.composer
```

## Changelog

### 1.0

* Initial release

## Author

* [Simon Bärlocher](https://sbaerlocher.ch)

## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2017, Simon Bärlocher