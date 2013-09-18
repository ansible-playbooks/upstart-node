Ansible / monit-web
===================

Ansible playbook to setup a Node.js Ubuntu service managed by Upstart.



Usage
-----

Create an inventory file with the servers that you want to Node.js on or use `$ANSIBLE_HOSTS`.

if connecting with root:

    ansible-playbook -i inventory-file -u root main.yml

if sudoing:

    ansible-playbook -i inventory-file -K main.yml



Ansible
-------

Not sure what Ansible is? Read the getting started here: http://procbits.com/2013/09/08/getting-started-with-ansible-digital-ocean


Upstart
-------

Read docs here: http://upstart.ubuntu.com/cookbook/



Todo
----

- make OS agnostic



License
-------

MIT/X11, Copyright 2013, JP Richardson