Role Name
=========

# Ansible Role: Nginx


Requirements
------------

None

Role Variables
--------------


Available variables are listed below, along with default values (see `vars/main.yml`):

```
nginx_version: "1.15.7"
pcre_version: "8.40"
zlib_version: "1.2.11"
openssl_version: "1.1.0f"
nginx_conf_path: "/etc/nginx/nginx.conf"
nginx_bin_path: "/usr/sbin/nginx"
nginx_log_dir: "/var/log/nginx"
nginx_user: www-data
nginx_group: www-data
download_path: "/tmp"
server_name: "Godzilla"
```

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: marvelleous.nginx }

License
-------

MIT / BSD

Author Information
------------------

This role was created in 2019 by [Tarun Singhal](https://www.linkedin.com/in/tarunsinghaldotme/).
