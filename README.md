# ansible-launch-webserver
The provided Ansible playbook configures Web servers on REDHAT and UBUNTU, installing the appropriate web servers packages, i.e, httpd for RedHat and apache2 for Ubuntu), copying the web pages into the pre defined directory /var/www/html and then starting the respective services. 
COnditional statement based on the `os_family` and `memfree_mb` fact ensures that each task is executed only on the targeted operating system. Adjust paths and service names as needed for your environment. 
Customize the file as per your requirements. 
