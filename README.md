# ansible-setup

Information on directory structure [here](https://docs.ansible.com/ansible/latest/user_guide/sample_setup.html)

## Setup

1. run `sudo ./setup.sh`
2. run `ansible-playbook -K ./playbook.yaml`

## Running on a remote machine

1. Add public ssh key to remote machine `ssh-copy-id -i ~/.ssh/id_rsa.pub user@remote-host`

