# docker-registry
run a simple ducker registry


# For SSL its required to have an SSL certificate in the cert directory
name them `domain.crt` and `domain.key`

## SimpleHtpasswdAuth is only for testing purposes, do not use them in production

## Requirements

* `docker service` : 
``` bash
sudo yum install -y yum-utils && yum-config-manager \
    --add-repo \
    https://download.docker.com/linux/centos/docker-ce.repo \
    && yum install -y docker-ce docker-ce-cli containerd.io docker-compose-plugin
```
* `htpasswd` : `sudo yum install apache2-utils`
