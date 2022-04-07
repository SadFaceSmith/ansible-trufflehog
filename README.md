ansible_trufflehog
=========

Automated GitHub scanning with [trufflehog](https://github.com/trufflesecurity/trufflehog)

Requirements
------------

* Ansible >= 2..9


Role Variables
--------------

| Variable  | Required  |Description   | Example   |   |
|---|---|---|---|---|
|
|repo  |yes  |Github Repo to scan   | grafana/loki  |   |



Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
```
---
  - name: Trufflehog automated scanning
    hosts: localhost
    connection: local
    become: no
    roles:
      - sadfacesmith.ansible_trufflehog
```      

Author Information
------------------

ethan@grafana.com | Grafana Labs Security Engineering
