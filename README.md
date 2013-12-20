An ansible role for installing zabbix agent.

Usage:
===

NOTE: gather_facts must be yes.

    ---
    - hosts: all
      remote_user: root
      roles:
      - resmo.zabbix-agent

Defaults:
===

Zabbix Server
---

`zabbix_server`. Default `zabbix.{{ ansible_domain }}`.

Listen IP:
---

`zabbix_agent_listen_ip`. Default `0.0.0.0`.

Node Hostname in Zabbix:
---

`zabbix_agent_hostname`. Default `{{ ansible_fqdn }}`.

Zabbix Agent install state:
---

Options: `latest|installed`
Note: `absent` is not yet possible. 

`zabbix_agent_state`. Default `installed`.

Homepage: 
===

https://github.com/resmo/ansible-role-zabbix-agent
