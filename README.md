
This Ansible role is for automated installation of NGINX proxy server 
on top of Galaxy framework. Production `mode` install server from sources
together with upload module and config sets uwsgi as web server.

### Usage ###
To use the role, you need to create a playbook and include this role in it.

### Variables ###
See `defaults/main.yml` for the available variables.

### Ubuntu 16.04 ###
To install NGINX from sources, one needs these:

```bash
sudo apt install libpcre3-dev libperl-dev libgeoip-dev
```