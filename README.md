UCLALib Ansible Role: Java: Ant
=========

Installs Apache Ant, a Java-based software build and deployment tool.

Requirements
------------

A JDK

Role Variables
--------------

 * ant_version: the full version number of the Ant binary you wish to install, defaults to 1.9.7

Dependencies
------------

 * [UCLALib Ansible Role: Java](https://github.com/UCLALibrary/ansible_uclalib_role_java)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

