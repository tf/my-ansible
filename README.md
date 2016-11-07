# My Ansible

Ansible Playbook to setup my computer

## Requirements

Tested on Ubuntu 16.04.

## Usage

Install Ansible via `apt`:

    $ bin/setup

Create variable file with secrets:

    $ cp vars/secrets.yml.example vars/secrets.yml

Apply playbook:

    $ bin/apply
