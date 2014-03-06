# Prosody Playbook

## Introduction
This [Ansible Role](http://docs.ansible.com) setups
[Prosody](https://prosody.im)

## Requirements

A fresh installed Centos (6.5) with root access and functioning ssh public key
login (see `ssh-copy-id`).

## How to use it

In the root of your playbook do:
```bash
git clone https://github.com/xsrc/prosody roles/prosody
```

Now you just have to add your hosts in your inventory to the `prosody` group

## Author
Bahtiar `kalkin` Gadimov
