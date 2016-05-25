# Ubuntu desktop configuration


## Usage

    cd ~/.config-desktop
    cp site-template.yml site.yml
    vim site.yml
    ansible-playbook -i hosts site.yml -K


## Installation
    sudo apt-get install software-properties-common
    sudo apt-add-repository ppa:ansible/ansible
    sudo apt-get update
    sudo apt-get install ansible
    sudo easy_install pip
    sudo pip install paramiko PyYAML jinja2
    git clone https://github.com/denislaliberte/config-desktop-ubuntu.git $HOME/.config-desktop


## Roadmap

- rvm, fix gpg key
- virtualenvwrapper test role, debug and chose
- fix postgresql role
- refactor pip task to requirements.txt file
- install shell script accessible by curl

- config if we need to use sudo
- fix chrome
