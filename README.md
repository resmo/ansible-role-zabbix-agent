[![Build Status](https://travis-ci.org/resmo/ansible-role-zabbix-agent.png?branch=master)](https://travis-ci.org/resmo/ansible-role-zabbix-agent)

# Ansible Zabbix Agent Role

Installing and configuraion of the Zabbix agent. Uses packages from http://www.zabbix.com.

## Usage
NOTE: `gather_facts` must be set to `yes`.

    ---
    - hosts: all
      remote_user: root
      gather_facts: yes
      roles:
      - resmo.zabbix-agent

## Dependencies
- resmo.zabbix-common (https://github.com/resmo/ansible-role-zabbix-agent)

## License
MIT

## Author Information
René Moser

## Homepage
https://github.com/resmo/ansible-role-zabbix-agent
