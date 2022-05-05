This repo is not maintained anymore. Please see https://github.com/dzangolab/ansible-docker-mailhog instead.


# Ansible Role: Install mailhog as a Docker container

An Ansible role to install [mailhog](https://github.com/mailhog/MailHog) as a Docker container.


## Requirements

This role requires Ansible 1.2 or higher.

## Role variables

Ansible variables are listed below with their default values.

```
mailhog_hostname
mailhog_network
mailhog_user
```

## Example playbook

```
---
- hosts: webservers
  roles:
  	- opichon.docker-services
```

## License

MIT

