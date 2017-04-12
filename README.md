# mage
A set of Ansible playbooks (originally authored and forked ones) to deploy containerized infrastructure on single 
physical hosts as well as clusters.

## Special purpose roles

- https://github.com/Vaizardmage-common
- https://github.com/Vaizardmage-vmhost
- https://github.com/Vaizardmage-update
- https://github.com/Vaizardmage-workstation

## Provisioning roles

- https://github.com/Vaizardmage.lxd-provisioning
- https://github.com/Vaizardmage.nginx-proxy
- https://github.com/Vaizardmage.letsencrypt

## HW related roles

- https://github.com/Vaizardmage-hw.dell9350

## Application & configuration roles

- Users, sudoers, ssh access. ftp access
  - https://github.com/Vaizardmage.users
  - https://github.com/Vaizardmage.sudo
  - https://github.com/Vaizardmage.openssh
  - https://github.com/Vaizardmage.vsftpd
- Databases
  - https://github.com/Vaizardmage.mysql [geerlingguy/ansible-role-mysql]
  - https://github.com/Vaizardmage.redis [geerlingguy/ansible-role-redis]
  - https://github.com/Vaizardmage.postgresql
- Mailstack
  - https://github.com/Vaizardmage.sovereign-common
  - https://github.com/Vaizardmage.sovereign-mailstack
  - https://github.com/Vaizardmage.sovereign-monitoring
  - https://github.com/Vaizardmage.sovereign-webmail
  - https://github.com/Vaizardmage.phplist
- Application
  - https://github.com/Vaizardmage.matrix-stack
  - https://github.com/Vaizardmage.nginx-app
- Administration
  - https://github.com/Vaizard/mage.adminer

## Dropped

Following playbooks have been superseeded by another solution

- https://github.com/Vaizardmage.mailtrain [see mage.phplist]
- https://github.com/Vaizardmage.mattermost [see mage.matrix-stack]

