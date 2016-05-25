# Ubuntu desktop configuration


## Usage

    source ~/ansible-desktop/.env
    avu # ansible vim ubuntu playbook
    apu # ansible execute playbook ubuntu
    


## Installation
    sudo apt-get install software-properties-common
    sudo apt-add-repository ppa:ansible/ansible
    sudo apt-get update
    sudo apt-get install ansible
    sudo easy_install pip
    sudo pip install paramiko PyYAML jinja2
    git clone https://github.com/denislaliberte/config-desktop-ubuntu.git $HOME/ansible-desktop


## Roadmap

* homyzsh, fix role, the shell is not changed
* vagrant, fix role, die at the apt-get vagrant
* homesick
* virutal box
* docker

* rvm, fix gpg key
* virtualenvwrapper test role, debug and chose
* fix postgresql role or create a role to configure postgres password and adminpack
* refactor pip task to requirements.txt file
* install shell script accessible by curl
* fix chrome
* [Ansible Galaxy | geerlingguy.nginx](https://galaxy.ansible.com/geerlingguy/nginx/)
* [Ansible Galaxy | geerlingguy.git](https://galaxy.ansible.com/geerlingguy/git/)
* [Ansible Galaxy | geerlingguy.apache](https://galaxy.ansible.com/geerlingguy/apache/)
* [Ansible Galaxy | geerlingguy.nodejs](https://galaxy.ansible.com/geerlingguy/nodejs/)
* [Ansible Galaxy | DavidWittman.redis](https://galaxy.ansible.com/DavidWittman/redis/)
* [Ansible Galaxy | geerlingguy.ruby](https://galaxy.ansible.com/geerlingguy/ruby/)
* [Ansible Galaxy | angstwad.docker_ubuntu](https://galaxy.ansible.com/angstwad/docker_ubuntu/)
* [Ansible Galaxy | franklinkim.nginx](https://galaxy.ansible.com/franklinkim/nginx/)
* [Ansible Galaxy | ANXS.postgresql](https://galaxy.ansible.com/ANXS/postgresql/)
* [Ansible Galaxy | joshualund.golang](https://galaxy.ansible.com/joshualund/golang/)
* [Ansible Galaxy | telusdigital.apt-repository](https://galaxy.ansible.com/telusdigital/apt-repository/)
* [Ansible Galaxy | Mayeu.RabbitMQ](https://galaxy.ansible.com/Mayeu/RabbitMQ/)
* [Ansible Galaxy | carlosbuenosvinos.ansistrano-deploy](https://galaxy.ansible.com/carlosbuenosvinos/ansistrano-deploy/)
* [Ansible Galaxy | ssilab.aws-cli](https://galaxy.ansible.com/ssilab/aws-cli/)
* [Ansible Galaxy | geerlingguy.jenkins](https://galaxy.ansible.com/geerlingguy/jenkins/)
* [Ansible Galaxy | nodesource.node](https://galaxy.ansible.com/nodesource/node/)
* [Ansible Galaxy | Stouts.ruby](https://galaxy.ansible.com/Stouts/ruby/)
* [Ansible Galaxy | Stouts.redis](https://galaxy.ansible.com/Stouts/redis/)
* [Ansible Galaxy | ansible-city.postgresql](https://galaxy.ansible.com/ansible-city/postgresql/)
* [Ansible Galaxy | telusdigital.python](https://galaxy.ansible.com/telusdigital/python/)
* [Ansible Galaxy | debops.apt_preferences](https://galaxy.ansible.com/debops/apt_preferences/)
* [Ansible Galaxy | martinmicunda.nodejs](https://galaxy.ansible.com/martinmicunda/nodejs/)
* [Ansible Galaxy | telusdigital.fish](https://galaxy.ansible.com/telusdigital/fish/)
