# Hosted Catalog App

## IP Address
54.245.194.217

## Url
[http://54.245.194.217.xip.io/](http://54.245.194.217.xip.io/)

## Software Installed
1. Apache
2. Python2.7
3. pip
4. Flask
5. mod_wsgi
6. ufw
7. ssh server

## Configurations
### Firewall
1. Turn off ssh on 22
2. Turn on ssh on 2200
3. Allow connections to 80/tcp.
4. Allow connections on 124/ntp.
5. Allow outgoing connections.
6. Deny all other incoming connections.

### User management
1. Turn off password authentication.
2. Add a user for grading with associated key.
3. Disable root access.

### Web server configuration
1. Configured flask to run as on Apache wsgi.

### Third party integration
1. Google OAuth2.0
