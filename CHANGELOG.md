# Ansible Role for GitLab CE

## 4.8.0 - TBC

### Major Changes

## 4.7.0 - 2021-03-13

### Major Changes

  - Bugfix [ansible-lint `namespace`](https://github.com/ansible-community/ansible-lint/pull/1451)
  - Bugfix [ansible-lint `no-handler`](https://github.com/ansible-community/ansible-lint/pull/1402)
  - Bugfix [ansible-lint `unnamed-task`](https://github.com/ansible-community/ansible-lint/pull/1413)
  - Install Python package with `pipx`
  - Simplify Python dependency with system packages
  - Support RHEL 8 with Molecule
  - Support RHEL 7 with Molecule
  - Remove CentOS 8 support
  - Improve HTTP transparent proxy support
  - Support CentOS 8 Stream
  - Support openSUSE Tumbleweed
  - Migrate base Vagrant box from `generic/*` to `alvistack/*`

## 4.6.0 - 2020-12-28

### Major Changes

  - Simplify Molecule scenario for vagrant-libvirt
  - Migrate from Travis CI to GitLab CI

## 4.5.0 - 2020-11-19

  - Ininitial release for Ansible 2.10 or higher
  - This role was designed for:
      - Ubuntu 18.04/20.04/20.10
      - RHEL/CentOS 7/8
      - openSUSE Leap 15.2
      - Debian 10
      - Fedora 33
