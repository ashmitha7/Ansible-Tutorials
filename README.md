# Ansible-Tutorials

Ansible is a configuration management software that lets you control and configure nodes from another machine.
What makes it different from other management software is that Ansible uses (potentially existing) SSH infrastructure,
while others (Chef, Puppet, ...) need a specific PKI infrastructure to be set up.

##Prerequisites
You need the following python modules on your machine (the machine you run ansible on)

    python-yaml
    python-jinja2

On Debian/Ubuntu run: sudo apt-get install python-yaml python-jinja2 python-paramiko python-crypto

Assuming you have a keypair in your ~/.ssh directory.

##Installing Ansible
From source

Ansible devel branch is always usable, so we'll run straight from a git checkout. 
You might need to install git for this (sudo apt-get install git on Debian/Ubuntu).

git clone git://github.com/ansible/ansible.git
cd ./ansible

At this point, we can load the Ansible environment:

source ./hacking/env-setup

##Goal
This repo will have multiple roles and modules amongst other ansible concepts that I'll be working on and everything
new I learn. Will have explaination of my errors and how I solved them for my beter understanding of Ansible.  
