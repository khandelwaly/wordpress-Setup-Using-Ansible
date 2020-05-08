## Ansible Playbook to setup wordpress
---
- How to run
```
ansible-playbook site.yml
```
--- 

- Workflow of this playbook

   It consists of 6 roles
   - update 
    
       It basically do **apt update**
   - python
   - mysql
   - php
   - nginx
   - wordpress
   - ssh_keys
