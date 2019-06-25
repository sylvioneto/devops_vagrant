# vagrant for dev environments
author: sylvio.pedroza@gmail.com

Vagrant repo with environments created for software development

## Pre-req:
- Vagrant => https://www.terraform.io
- Virtualbox =>  https://www.virtualbox.org/wiki/Downloads
- Ansible => https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html?extIdCarryOver=true&sc_cid=701f2000001OH7YAAW#intro-installation-guidecking

## Usage
- clone the repo
- cd env_*
- vagrant up (create and start vms)
- vagrant halt (shutdown vms)
- vagrant ssh [vm] (connects to the specific vm)

## Ansible
Recommended setup https://docs.ansible.com/ansible/latest/user_guide/intro_getting_started.html#host-key-checking

## Addition notes
Remember to create a rsa key pair named id_rsa_vagrant.
Then, copy the .pub key to the env/config folder.