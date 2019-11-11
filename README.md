# Ansible Playbook for Spinnaker Installation

### Setup

```bash
$ git clone git@github.com:rajivreddy/spinnaker-ansible.git
$ cd spinnaker-ansible

```

- Update Hosts inventory file
- Change user from Vagrant to ubuntu

#### Note

- Make sure your Ansible workstation have access to Remote server(add your public key to it)

### Usage

```bash
$ ansible-playbook playbook.yml

PLAY [apply common configuration to all nodes] ***************************************************************************************************

TASK [Gathering Facts] ***************************************************************************************************************************
ok: [192.168.33.100]


```