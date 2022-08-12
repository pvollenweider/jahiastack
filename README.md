# jahiastack
This is a dev stack for Jahia including a haproxy fron, a jcustomer with elasticsearch and a mariadb.
Data are persistant.

To run the docker simply execute the commande 
```
git clone https://github.com/pvollenweider/jahiastack.git
cd jahiastack
docker-compose up
```
Once started, a provisioning script install and configure jexperience, some bootstrap 5 bundles and create an empty site.
Access the site with the following URL http://localhost:18080
