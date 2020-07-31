# DevOps Tools

## Docker

### Run docker as non-root user in Linux
      Run the following commands to add user in the docker group:
      $ sudo groupadd docker
      $ sudo usermod -aG docker $USER
      $ newgrp docker
      
      That's it.
      $ docker version 
     

## Jenkins

## Ansible

## Terraform

## Kubernetes
<blockquote>
   
### VirtualBox
   [Add virtualbox repositor and install following this link](https://computingforgeeks.com/how-to-install-latest-virtualbox-on-ubuntu-debian/)
 B
### Minikube
   [Install Minikube following this link](https://phoenixnap.com/kb/install-minikube-on-ubuntu)

### kubectl
   [Install kubectl on Linux following this link](https://kubernetes.io/docs/tasks/tools/install-kubectl/)

</blockquote>

Few other important servers:

## Kafka
[Install Apache Kafka on Ubuntu 20.04 LTS](https://www.fosstechnix.com/how-to-install-apache-kafka-on-ubuntu-20-04-lts/)

[How to install and run Kafka on your machine](https://www.sohamkamani.com/blog/2017/11/22/how-to-install-and-run-kafka/)

[Microservices, Event-Driven Architecture and Kafka](https://dzone.com/articles/microservices-event-driven-architecture-and-kafka)

## ELK Stack


## MongoDB
 [Install MongoDB on Ubuntu 20.04](https://linuxhint.com/install_mongodb_ubuntu_20_04/) in an easy way. It may not install up-to-date version. To install the latest comunity edition on your preferred platform using your preferred package manager, please follow the link below:
 [Install MongoDB Community Edition](https://docs.mongodb.com/manual/administration/install-community/)
 
 ## HAProxy 
 [HAProxy](https://www.haproxy.com/) is a free, very fast and reliable solution offering high availability, load balancing, and proxying for TCP and HTTP-based applications. Please see the following link:
 [Load Balancing using HAProxy](https://www.digitalocean.com/community/tutorials/an-introduction-to-haproxy-and-load-balancing-concepts)
 [How to use HAProxy for Loadbalancing](https://www.linode.com/docs/uptime/loadbalancing/how-to-use-haproxy-for-load-balancing/)
 
 ## Testing Tools:  
 <hr/>
 
 ### SonarQube
 [SonarQube](https://www.sonarqube.org/) is an open-source platform for continuous inspection of code quality to perform automatic reviews with static analysis of code to detect bugs, code smells, and security vulnerabilities.
 
 ### PMD
 
 ### Checkstyle
 [Checkstyle](https://github.com/checkstyle/checkstyle) is a static code analysis tool for checking if Java source code complies with coding rules. This tool is fully configurable to your preferences such as [Sun Code Conventions](https://www.oracle.com/java/technologies/javase/codeconventions-contents.html) or [Google Java Style](https://checkstyle.sourceforge.io/reports/google-java-style.html).
 
 ### FindBugs
 
 ### Codacy
