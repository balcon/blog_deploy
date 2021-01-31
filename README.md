## Downlod and deploy
**Docker-compose** must be installed on your host system.
Copy to clipboard and execute
```bash
wget https://github.com/balcon/blog_deploy/archive/v0.9.tar.gz -O blog.tar.gz
tar xvfz blog.tar.gz
cd blog_deploy-0.9
sudo docker-compose up -d
```
- http://<host_ip>:80 - Wordpress site
- http://<host_ip>:8080 - database Adminer
- http://<host_ip>:3000 - Grafana monitoring (admin/admin by default)


