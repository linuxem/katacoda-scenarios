
## In this step you will build your own docker:

`docker build -t nginx:elbit .`{{execute}}

## Run your docker:

`docker run -d -p 81:80 nginx:elbit`{{execute}}

## Test your docker:

https://[[HOST_SUBDOMAIN]]-81-[[KATACODA_HOST]].environments.katacoda.com
