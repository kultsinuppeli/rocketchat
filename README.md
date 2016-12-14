# Ansible playbook for RocketChat

This playbook sets up [RocketChat](https://rocket.chat/). The server will request a [Let's Ecrypt](https://letsencrypt.org) certificate for its hostname.

## Requirements

Ansible >= 2.2

## Usage

Add correct server names to the inventory file.
Set correct remote_user in ansible.cfg.

Set letsencrypt_email in group_vars/all/letsencrypt.yml
Set rocket domains in group_vars/all/domains.yml
Run mkdir roles

Run ansible-galaxy install -r requirements.yml

Run the site.yml playbook.

## Author

Kalle Happonen (https://github.com/kultsinuppeli/)
