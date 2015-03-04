
Role to install and configure SNMP packages on RedHat and Debian based systems.
This role has been tested on the following OSs:
--CentOS 6.5
--Ubuntu 12.04 

Requirements
------------

None

Role Variables
--------------

OS specific variables are defined in /vars/{{ ansible_os_family }}.yml files. 
Default variables are defined in /defaults/main.yml
The SNMP Community String can be defined in the /defaults/main.yml file

Dependencies
------------

None

Example Playbook
----------------

    - hosts: all
      roles:
         - snmp

License
-------

BSD

Author Information
------------------

This role was authored by Yohan | 2015.

