# Useful certbot commands
- This Dockerfile contains installation steps to install certbot with nginx plugin using nginx:latest docker image along with various utils
  
- Certbot with http challenage and nginx plug in
```bash
certbot --nginx -d example.com
certbot --nginx -d subdomain.example.com
```
- Link to dockerhub image
  [nginxcertbot](https://hub.docker.com/r/dhananjay1992/nginxcertbot)