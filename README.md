## If you got below error 
TASK [jenkins : Execute RHEL tasks] ************************************************************************************************************************
ERROR! couldn't resolve module/action 'ansible.posix.firewalld'. This often indicates a misspelling, missing collection, or incorrect module path.

The error appears to be in '/home/manku/workspace/ansible_workspace/ansible-playbooks/jenkins/tasks/rhel.yml': line 50, column 3, but may
be elsewhere in the file depending on the exact syntax problem.

The offending line appears to be:


- name: rhel | Open Firewall Port
  ^ here

## Install the below package using command 
  #  ansible-galaxy collection install ansible.posix 
