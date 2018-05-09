### Install  Nginx + php-fpm 7.2 + mariadb on CentOS 7

In file option.yml can choose install option
```YAML
---
repo_git: https://github.com/WordPress/WordPress.git
domain: site.net
server_listen: "10.0.10.2"
server_name: "site.net www.site.net"
index: "index.php"
cms: "wp"
fastcgi_pass: "127.0.0.1"
fastcgi_pass_port: "9000"
mysql_db: "wp"
mysql_user: "user_db"
mysql_pass: "StRonG_PasSw0rd"
fastcgi_pass_cache: "on"
####Use SSL
use_ssl: "on"
port_ssl: "443"
ssl_pem: "site.pem"
ssl_key: "site.key"
```
To disable option, comment on them
