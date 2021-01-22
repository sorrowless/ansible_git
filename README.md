# sbog/git

[![Build Status](https://travis-ci.com/sorrowless/ansible_git.svg?branch=master)](https://travis-ci.com/sorrowless/ansible_git)
[![Ansible Role](https://img.shields.io/ansible/role/52814)](https://galaxy.ansible.com/sorrowless/git)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/52814)](https://galaxy.ansible.com/sorrowless/git)
[![Ansible Role](https://img.shields.io/ansible/role/d/52814)](https://galaxy.ansible.com/sorrowless/git)
[![GitHub](https://img.shields.io/github/license/sorrowless/ansible_git)](https://github.com/sorrowless/ansible_git/blob/master/LICENSE)

An Ansible role which allow to securely pull git repos to target host without
saving credentials for the target repositories on host itself.

## Requirements

Ansible 2.7+

## Role Variables

You can see all vars in `defaults/main.yml` vars file.

## Dependencies

None

## Example Playbook

```yaml
- name: Ensure git clone of needed repositories
  hosts: all
  remote_user: root

  roles:
    - git
```

## License

Apache 2.0

## Author Information

This role was created by [Stan Bogatkin](https://sbog.ru).
