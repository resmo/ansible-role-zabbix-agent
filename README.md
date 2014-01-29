[![Build Status](https://travis-ci.org/resmo/ansible-role-zabbix-agent.png?branch=master)](https://travis-ci.org/resmo/ansible-role-zabbix-agent)

# Ansible Zabbix Agent Role
An ansible role for installing zabbix agent.


## Usage
NOTE: gather_facts must be yes.

    ---
    - hosts: all
      remote_user: root
      roles:
      - resmo.zabbix-agent

## License
MIT

## Author Information
René Moser

## Homepage
https://github.com/resmo/ansible-role-zabbix-agent
