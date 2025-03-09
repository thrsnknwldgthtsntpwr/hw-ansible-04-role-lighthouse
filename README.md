Lighthouse-role
=========

This role allows you to install Lighthouse on Debian-based distos via a [github repo](https://github.com/VKCOM/lighthouse.git).        

Requirements
------------

git and nginx 

Role Variables
--------------

| vars | Description | Value | Location |
|------|------------|---|---|
| lighthouse_dir | a directory to store Lighthouse files | "/home/{{ ansible_user_id }}/lighthouse" | defaults/main.yml |
| lighthouse_url | URL of Lighthouse repo | "https://github.com/VKCOM/lighthouse.git" | vars/main.yml |



License
-------

MIT

Author Information
------------------

Roman Nikiforov