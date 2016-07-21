ansible-role-eclipse [![Build Status](https://travis-ci.org/caarlos0/ansible-role-eclipse.svg?branch=master)](https://travis-ci.org/caarlos0/ansible-role-eclipse)
=========

An ansible role that installs an configures an Eclipse IDE with Java EE support
and some tweaks to improve performance.

It will download Eclipse JEE, install some plugins, install lombok,
tune some configs, remove some useless stuff, and create the needed links.

Requirements
------------

- Java JDK (can be installed with
[caarlos0.java-dev](https://github.com/caarlos0/ansible-role-java-dev) role).


Example Playbook
----------------

You can use it like:

```yml
- hosts: servers
  roles:
    - caarlos0.eclipse
```

Install in your computer
------------------------

If you just want to run this in your machine, you can:

```console
$ git clone https://github.com/caarlos0/ansible-role-eclipse
$ cd ansible-role-eclipse
$ ./setup
```

- You'll need Ansible 2.2+ installed;
- Running this will also install JDK 7 and 8, as well maven and gradle.

License
-------

MIT

Old version
-------

The previous version (bash script) can be found in the
[old branch](https://github.com/caarlos0/ansible-role-eclipse/tree/old).
