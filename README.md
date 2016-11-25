# Ansible docker role
Simple ansible role to install the docker engine

## Installation
Include this in your requirements.yml file
```
- src: https://github.com/fxleblanc/ansible-role-docker
  name: docker
```

## Usage
Specify the docker role in your playbook
```
- hosts: all
  become: true
  roles:
    - docker
```

## Testing
Clone the repository
```
git clone https://github.com/fxleblanc/ansible-role-docker
```
Launch the vagrant vm
```
vagrant up
```
