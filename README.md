ansible-role-eclipse
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

License
-------

BSD
