# Dockerfile for Laravel
Laravel Compose ready docker image for development

## This has the following features
* Compatible with MSSQL 2005
    * Ready for using MSSQL 2005 as DB
* www root = /var/www/html/project/public

# Installation Guide
    1)Clone Or Download The Repository
    
    2)Goto The Repository and Open a Terminal
    
    3)Create network pool :
        docker network create  --driver=bridge --subnet=10.28.0.0/16 --ip-range=10.28.5.0/24 --gateway=10.28.5.254  br0

    4)Build image :
        docker-compose up -d --build

# Todo
Completed readme.md
