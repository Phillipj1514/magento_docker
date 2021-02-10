# magento_docker
Docker setup for a magento open source website.

*Note: If the project is been used in production change all the passwords to something secure*

-------------

##  1 Install and build images

`
docker-compose build
` 

##  2 start images

`
docker-compose up -d
` 

## 3 install magento

`
docker exec -it (foldername)_php_(number instance) /install
eg.
docker exec -it magento_docker_php_1 /install
` 
