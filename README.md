# My Ansible

Ansible Playbook to setup my computer

## Requirements

Tested on Ubuntu 20.04.

## Usage

Install Ansible via `apt`:

    $ bin/setup

Create variable file with secrets:

    $ cp vars/secrets.yml.example vars/secrets.yml

Apply playbook:

    $ bin/apply

## Missing

* bin/tfpass
* bin/spotify-control and key bindings
* GitHub CLI
