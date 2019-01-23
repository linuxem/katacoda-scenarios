
For example `docker run -d -p 80:80 -v $PWD:/usr/share/nginx/html nginx`{{execute}}

Test The Link

https://[[HOST_SUBDOMAIN]]-80-[[KATACODA_HOST]].environments.katacoda.com

You can try more docker images to run from 
https://hub.docker.com/search?q=&type=image
For example running jenkins
'docker run -d -u root --name jenkins \
    -p 8080:8080 -p 50000:50000 \
    -v /root/jenkins_2112:/var/jenkins_home \
    jenkins/jenkins:2.112-alpine' {{execute}}



