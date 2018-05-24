# ansible-django

An Ansible Playbook for quickly getting any Django web app up and running on CentOS-7.

This playbook installs and configures the following applications:

    * Python (latest version from source)
    * Nginx
    * PostgreSQL
    * Virtualenv
    * Django

## Requirements

### Ansible (v1.6.10)

#### Installation

##### Ubuntu
    
    sudo apt-get install software-properties-common
    sudo apt-add-repository ppa:ansible/ansible
    sudo apt-get update
    sudo apt-get install ansible

##### Mac
    
    brew update
    brew install ansible

### SSHPass (v.1.05)

#### Installation

##### Ubuntu

    sudo apt-get install sshpass

##### Mac

    cd ~/Downloads
    curl -O -L http://downloads.sourceforge.net/project/sshpass/sshpass/1.05/sshpass-1.05.tar.gz
    tar xvzf sshpass-1.05.tar.gz
    cd sshpass-1.05

    ./configure
    make
    sudo make install

## Getting Started

## Playing on a real cloud server

## Playing with your own web app
