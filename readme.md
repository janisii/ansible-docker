### Install Docker with Ansible

Add custom user name in `vars.yaml` file for running docker containers on system and update `hosts` file to add hosts. To connect to hosts you have to provide `remote_user` which can be updated in `ansible.cfg` file. Don't forget to add remote user to sudo group. 

Important! Playbook can be used ONLY on Ubuntu or Debian nodes.

Usage:

```commandline
$ ansible-playbook docker_playbook.yaml
```

Ansible cannot be installed on Windows.

