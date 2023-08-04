Role Name
=========

jenkins

Requirements
------------
Required RHEL9 OS\
Ansible package\
Refer this https://medium.com/@jaine.mayank/how-to-install-ansible-on-rhel9-step-by-step-b462237f229e to install the Ansible

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

python\
pip\
ansible.posix.firewalld module can install using below command\ 
#ansible-galaxy collection install ansible.posix

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    ---
    - name: jenkins Playbook
      hosts: 127.0.0.1
      tasks:
        - name: Include jenkins
          ansible.builtin.include_role:
          name: jenkins
