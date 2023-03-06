# keycloak-nginx

Demo project that uses NGINX as a reverse proxy(load balancer) with SSL termination to Keycloak. 

Note: In a production application you would want to secure this by restricting access to Keycloak to only NGINX’s IP, 
or have this is a private network - this project does not handle that. 
