# ansible-setup

Information on directory structure [here](https://docs.ansible.com/ansible/latest/user_guide/sample_setup.html)

## Setup

1. run `sudo ./setup.sh`
2. run `ansible-galaxy install -r requirements.yml`
3. run `ansible-playbook -K ./playbook.yaml`

## Running on a remote machine

1. Add public ssh key to remote machine `ssh-copy-id -i ~/.ssh/id_rsa.pub user@remote-host`


## Host notes

### raspberrypi1 

- Remove `nt pipe support = no` from `/etc/samba/smb.conf` after running
- The hdd is mounted at /mnt/backups
    - make a folder in here for each user (have a user per pc backup)
    - set the permissions so only that user can access that folder

