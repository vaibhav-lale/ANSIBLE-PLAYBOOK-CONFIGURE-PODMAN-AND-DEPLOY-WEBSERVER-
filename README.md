# ANSIBLE-PLAYBOOK-CONFIGURE-PODMAN-AND-DEPLOY-WEBSERVER
This playbook install & configure podman service, pull the httpd image from Docker Hub, run the httpd container, copy the HTML code 
in container using podman volume and exposes the container to the public by port forwarding.

Some steps to verify the task:
Using this command you will enter into container httpd - sudo podman exec -it (container ID) bash
Change directory to htdocs and open index.html to verify the code copied using attached volume.
 cd htdocs/
 cat index.html
 
