## Udacity Project - linux-server-config

Server configurations
1. IP address and SSH port: *13.126.209.41:2200*
2. complete URL to your hosted web application: [13.126.209.41/catalog](http://13.126.209.41/catalog)
3. summary of packages installed and configuration changes made is as follows
### Flask - Web Framework used
### oauth2client - for authentication and authorization
### passlib - for generating hash_passwords
### SQLAlchemy - Python SQL toolkit and Object Relational Mapper
### PostgreSQL - Database engine
postgresql involves a role 'catalog' which is used to connect to underlying database
### remote login as root is diabled
### ssh port is 2200
### a gradee user is creadted, key is provided in reviewer notes.
4. A list of any third-party resources: only for server setup which is done on Amazon LightSail


## About the Application
This app consists of displaying items corresponding to catalogs. Addition, Updation and Deletion can be performed on Items but Catolog list is fixed. Item description is also available
Currently no validations are added on Items,Catalogs and user email addresses.