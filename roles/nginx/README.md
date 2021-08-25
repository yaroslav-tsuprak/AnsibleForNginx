# Ansible Role: Nginx

Installs Nginx on Ubuntu Linux server.

This role installs and configures the latest version of Nginx from the Nginx apt repository.
You will likely need to do extra setup work after this role has installed Nginx, like adding your own [virtualhost].conf file inside `/etc/nginx/conf.d/`, describing the location and options to use for your particular website.

## Requirements

None.

## Author

Yaroslav Tsuprak
