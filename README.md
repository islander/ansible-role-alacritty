Alacritty
=========
[![Build Status](https://travis-ci.org/islander/ansible-role-alacritty.svg?branch=master)](https://travis-ci.org/islander/ansible-role-alacritty)

A role to install [alacritty][1] terminal emulator.

Requirements
------------

Ansible control node requires [python-jmespath][2] to get latest release URL from github API.

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):
```
alacritty_release_url: https://api.github.com/repos/alacritty/alacritty/releases/latest
```
API URL of wal-g github releases.

Example Playbook
----------------
Install role from galaxy: `ansible-galaxy install islander.alacritty`

    - hosts: servers
      roles:
         - islander.alacritty

License
-------

BSD

Author Information
------------------

This role was created by [kiba][3]

[1]: https://github.com/alacritty/alacritty
[2]: https://pypi.org/project/jmespath/
[3]: https://kiba.io
