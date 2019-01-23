
This step you will build you own docker 
`cd myDocker`{{execute}}

`docker build -t nginx:elbit .`{{execute}}

Run you new docker 

`docker run -p 81:80 nginx:elbit`{{execute}}

Test your docker 

https://[[HOST_SUBDOMAIN]]-81-[[KATACODA_HOST]].environments.katacoda.com
