ansible-role-eclipse [![Build Status](https://travis-ci.org/caarlos0/ansible-role-eclipse.svg?branch=master)](https://travis-ci.org/caarlos0/ansible-role-eclipse)
=========

An ansible role that installs an configures an Eclipse IDE with Java EE support
and some tweaks to improve performance.

It will download Eclipse JEE, install some plugins, install lombok,
tune some configs, remove some useless stuff, and create the needed links.

Requirements
------------

- Java JDK


Example Playbook
----------------

You can use it like:

```yml
- hosts: servers
  roles:
    - caarlos0.eclipse
```

If you just want to run this in your machine, you can:

```console
$ git clone https://github.com/caarlos0/ansible-role-eclipse
$ cd ansible-role-eclipse
$ ansible-playbook tests/test.yml -i tests/inventory
```

You might need to use `sudo` on Ubuntu machines.

License
-------

MIT
