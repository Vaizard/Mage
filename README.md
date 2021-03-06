# mage
A set of Ansible playbooks (originally authored and forked ones) to deploy containerized infrastructure on single 
physical hosts as well as clusters.

## Special roles

- Base roles
  - https://github.com/Vaizard/mage-common
  - https://github.com/Vaizard/mage-vmhost
  - https://github.com/Vaizard/mage-update
  - https://github.com/Vaizard/mage-workstation
- Provisioning roles
  - https://github.com/Vaizard/mage.lxd-provisioning
  - https://github.com/Vaizard/mage.nginx-proxy
  - https://github.com/Vaizard/mage.letsencrypt
- HW related roles
  - https://github.com/Vaizard/mage-hw.dell9350

## Application & configuration roles

- Virtualization
  - https://github.com/Vaizard/mage.libvirt
- Users, sudoers, network (ssh, ftp, nfs)
  - https://github.com/Vaizard/mage.users
  - https://github.com/Vaizard/mage.sudo
  - https://github.com/Vaizard/mage.openssh
  - https://github.com/Vaizard/mage.vsftpd
  - https://github.com/Vaizard/mage.fail2ban [Oefenweb/ansible-fail2ban]
  - https://github.com/Vaizard/mage.nfs [https://github.com/geerlingguy/ansible-role-nfs]
- Databases
  - https://github.com/Vaizard/mage.mysql [geerlingguy/ansible-role-mysql]
  - https://github.com/Vaizard/mage.redis [geerlingguy/ansible-role-redis]
  - https://github.com/Vaizard/mage.postgresql
- Mailstack
  - https://github.com/Vaizard/mage.sovereign-common
  - https://github.com/Vaizard/mage.sovereign-mailstack
  - https://github.com/Vaizard/mage.sovereign-monitoring
  - https://github.com/Vaizard/mage.sovereign-webmail
  - https://github.com/Vaizard/mage.phplist
- Application
  - https://github.com/Vaizard/mage.matrix-stack
  - https://github.com/Vaizard/mage.nginx-app
  - https://github.com/Vaizard/mage.apache-app
  - https://github.com/Vaizard/mage-git
  - https://github.com/Vaizard/mage.gogs
- Administration and backups
  - https://github.com/Vaizard/mage.adminer
  - https://github.com/Vaizard/mage.pimpmylog
  - https://github.com/Vaizard/mage.borgbackup
- MS Windows roles
  - https://github.com/Vaizard/mage.mswindows

## Dropped

Following playbooks have been superseeded by another solution

- https://github.com/Vaizard/mage.mailtrain [see mage.phplist]
- https://github.com/Vaizard/mage.mattermost [see mage.matrix-stack]

## Cheatsheet

Add key to ssh-agent

```
eval $(ssh-agent -s)
ssh-add ~/.ssh/id_rsa
```
