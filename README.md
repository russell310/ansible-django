## Django-Ansible

#### Host django site on your favorite vps

#### Steps:

1. Clone project
2. Change on `env_vars/base.yml` file as your requirements
3. Put command `ansible-playbook -i inventory webserver.yml`
4. Take a tea break

N.B:

* If you want uwsgi over gunicorn change `webserver.yml` file
* Run this on local machine
* Must have ssh access to server from local machine
* Project must have ssh access from server