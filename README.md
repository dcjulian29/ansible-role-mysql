# Ansible Role: mysql

[![Lint](https://github.com/dcjulian29/ansible-role-mysql/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-mysql/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-mysql.svg)](https://github.com/dcjulian29/ansible-role-mysql/issues)

This an Ansible role to install MySQL Server.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.mysql
  src: https://github.com/dcjulian29/ansible-role-mysql.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
