## Ansible Playbook to setup wordpress
---
- How to run
```
ansible-playbook site.yml
```
--- 

- Workflow of this playbook

   It consists of 6 roles
   - **update:-**   It basically do **apt update**
   - **python:-**   For setiing up python
   - **mysql:-**    Installing mysql and creating user and db for wordpress
   - **php:-**      For setting up php-fpm
   - **nginx:-**    Installing nginx and 
   - **wordpress:-**   Downloading wordpress and changing its wp-config.php
   - **ssh_keys:-**   If you have multiple users, then define ***user names*** and their path of their ***id_rsa.pub*** in ssh_keys/tasks/main.yml and it will copy their keys in ***authorized_keys*** file on server   
