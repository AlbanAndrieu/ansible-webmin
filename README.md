ansible-webmin
====================

A role for installing webmin.

[![Build Status](https://api.travis-ci.org/AlbanAndrieu/ansible-webmin.png?branch=master)](https://travis-ci.org/AlbanAndrieu/ansible-webmin)

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
