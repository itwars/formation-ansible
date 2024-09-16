# Getting starting with Ansible with a Docker LAB 🐳

This repo is part of my [blog post](http://www.it-wars.com/posts/dev/formation-ansible-docker-devops/) on geting started with Ansible and becoming a DevOps.

## The LAB

- Docker Ubuntu

Plus a Docker Ansible, to have and avoid installing Ansible on your laptop.

## Bootstrap Ansible LAB

To bootstrap this tutorial, I wrote and [init script](https://github.com/itwars/ansible-101/blob/master/02-init-sshkey.sh), by doing following tasks:

- Delete previous 3 containers Debian, Ubuntu et Alpine
- Create an RSA key allowing Ansible connection through SSH
- Starting 3 instances Docker Debian, Docker Ubuntu, and Docker Alpine
- Ssh key injection in each Docker instance using ssh-copy-id (password will be ask: **toor**)
- Ansible hosts inventory creation

