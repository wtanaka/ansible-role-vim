[![Build Status](https://travis-ci.org/wtanaka/ansible-role-vim.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-vim)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-vim.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-vim)

wtanaka.vim
===========

This ansible role installs vim

Example Playbook
----------------

    - hosts: all
      roles:
         - wtanaka.vim

### `vim_should_shortcircuit`

Default: True

When True, this role short-circuits itself if a "vim" is already in the path

### All variables

The full set of configuration options available are visible in
[defaults/main.yml](defaults/main.yml)

License
-------

GPLv2

Author Information
------------------

http://wtanaka.com/
