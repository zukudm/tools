# Tools: Prepare Nodes environment for docker installation and others helping tools

## Prepare the environment

Playbook install_docker.yml is intended to prepare a Linux box for node installation.

Log in inside the Linux box and run

```bash
 git clone https://github.com/zukudm/tools.git
 cd tools
 ansible-galaxy install -r collections/requirements.yml
 ansible-playbook install_docker.yml
```
In case of a problem run install_docker2.yml

## Install a Managing and Real-time monitoring tool

Playbook Portainer.yml is intended to install a managing and real-time monitoring tool on the Linux box.

Log in inside the Linux box and run

```bash
 git clone https://github.com/zukudm/tools.git
 cd tools
 ansible-galaxy install -r collections/requirements.yml
 ansible-playbook Portainer.yml
```

### Don't forget to log in and change the password after running  Portainer.yml!!!

Log in using the Linux box IP like http://input linux ip here:9000

Set up a password for the admin user.


