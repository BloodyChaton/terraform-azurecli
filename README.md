Role Name
=========

This role sets up 
- Terraform v 0.11.14
- AZURE CLI to connect to Microsoft Azure CSP

Requirements
------------

Centos 7


Example Playbook
----------------

Example: run locally 
Create a {name}.yml playbook:

- name: Deploy Terraform
  hosts: 127.0.0.1
  connection: local
  become: yes
  become_method: sudo
  roles:
    - { role: bloodychaton.terraform }


Then use command: $ ansible-playbook -K {name}.yml


License
-------

Used allowed if the author is mentionned. Modifications allowed if author is mentioned.

Author Information
------------------

github.com/BloodyChaton