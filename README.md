FaucetSDN ansible role
======================




Requirements
------------

Operating system:
* Debian 9 stretch
* Debian 10 buster

Ansible:
* > 2.2


Playbooks
---------
We have following playbooks:
* setup.yml


How use it
----------

> ansible-playbook -i inventory/localhost setup.yml -vvv

without applying changes

> ansible-playbook -i inventory/localhost setup.yml -vvv --check 

and showing the differences

> ansible-playbook -i inventory/localhost setup.yml -vvv --check --diff
