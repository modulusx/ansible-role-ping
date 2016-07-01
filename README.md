Ping
=========
Might ping any common type of host.

Installation
--------------
```
ansible-galaxy install modulusx.ping
```

Example Playbook
----------------
```
- hosts: all
  gather_facts: False
  roles:
    - { role: modulusx.ping }
```

License
-------
MIT
