## Simple Java Form deployed using DevOps  

This is a simple form written in Java. This form is deployed using docker and ansible and Jenkins has been used as the CI tool .
The war file geenrated using maven is deployed to ansible server and the ansible is creating the docker image and pushing it to dockerhub and another playbook is written to download the docker image, build a container and host it in tomcat server
