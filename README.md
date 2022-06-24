# Weight-Tracker-Ansible


The playbook:
1. install nodejs and npm.
2. clones the Weight-Tracker application from github.
3. updates the .env file of Weight-Tracker application.
4. install the project npm dependencies.
5. install pm2 and uses it to run the application.
6. 

To use the playbook, you should create a file vars.yml in the same folder of the playbook.

The file should have:
```
---
  PORT: 
  LB_IP: 
  PGHOST: 
  PGUSERNAME: 
  PGDATABASE: 
  PGPASSWORD: 
  COOKIE_ENCRYPT_PWD: 
  OKTA_ORG_URL: 
  OKTA_CLIENT_ID: 
  OKTA_CLIENT_SECRET: 
```
  
  
You should fill the variables.
