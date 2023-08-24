Role Name
=========

Ansible Role to install and configure Squid Proxy on RHEL9

Requirements
------------

### Linux OS recommended RHEL8 or RHEL9
### Ansible Package installed on OS

Role Variables
--------------

Variables are store in defaults/main.yml file which contains deafults squid.conf file variables. 


Dependencies
------------

RHEL9 OS should have subscription manager or epel repo should be configure to download and install squid package. 

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
         - squidProxy
