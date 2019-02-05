## Start nginx Server:

`docker run -p 80:80 -d nginx`{{execute}}

## Test Web Link:

https://[[HOST_SUBDOMAIN]]-80-[[KATACODA_HOST]].environments.katacoda.com

## Now see the Databasen Docker 

`docker pull microsoft/mssql-server-linux`{{execute}}

`docker images`{{execute}}

## You can run this image like this 

`docker run -e 'ACCEPT_EULA=Y' -e 'SA_PASSWORD=yourStrongPassword' -p 1433:1433 -d microsoft/mssql-server-linux:2017-latest`{{execute}}

## Check the Docker 

`docker exec -it /opt/mssql-tools/bin/sqlcmd -S localhost -U sa -P`{{execute}}






 
