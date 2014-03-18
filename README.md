#Prosody


## Goal

The goal of this role is to simplify jabber server deployment for private needs.

## Requirements

Installed elpa sources

## Role Variables
- `prosody_hostname` Hostname to listen to. Default `{{ ansible_hostname }}`
- `prosody_registration` Default true You are running an jabber server, for your
  private needs? Why not to share it with others?
- `prosody_admin`: Default to `admin@"{{ansible_hostname}}"`. The role DOES NOT
  create the admin user. You can use prosodyctl command or a jabber client for
  this (if you enabled `prosody_registration`).


## Dependencies
EPEL Repositories 

## Author
kalkin https://github.com/xsrc/
