ansible-webmin
====================

A role for installing webmin.

[![Build Status](https://api.travis-ci.org/AlbanAndrieu/ansible-webmin.png?branch=master)](https://travis-ci.org/AlbanAndrieu/ansible-webmin)
[![Galaxy](http://img.shields.io/badge/galaxy-webmin-blue.svg?style=flat-square)](https://galaxy.ansible.com/list#/roles/1173)
[![Tag](http://img.shields.io/github/tag/AlbanAndrieu/ansible-webmin.svg?style=flat-square)]()

## Actions

- Ensures that webmin is installed (using `apt`)

Usage example
------------

    - name: Install webmin
      hosts: webmin
      user: root
    
      roles:
        - webmin      

Requirements
------------

none

Dependencies
------------

none

License
-------

MIT

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/AlbanAndrieu/ansible-webmin/issues)!
