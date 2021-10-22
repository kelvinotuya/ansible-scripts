#Ansible Roles
## Example in Continuous Delivery where I am deploying a new build of my J2EE application (WAR file) to tomcat my steps would be as follows:
##  i. Stop application, ii. uninstall the application, iii. deploy the new build of an application, iv. start the new application

###  $ cd /etc/ansible/roles
###  $ sudo ansible-galaxy init tomcat --offline

