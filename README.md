# Ansible Zabbix Agent Role
An ansible role for installing zabbix agent.

[![Build Status](https://travis-ci.org/resmo/ansible-role-zabbix-agent.png?branch=master)](https://travis-ci.org/resmo/ansible-role-zabbix-agent)

## Usage:

NOTE: gather_facts must be yes.

    ---
    - hosts: all
      remote_user: root
      roles:
      - resmo.zabbix-agent

## Homepage: 

https://github.com/resmo/ansible-role-zabbix-agent
