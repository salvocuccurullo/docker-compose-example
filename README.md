
* Install docker compose https://docs.docker.com/compose/install/

---

Build (in this example it's no needed since mysql image is fetched from docker hub) 

`docker-compose build`


 starts all services (containers)

`docker-compose up -d`

 stops all services (containers)
	
`docker-compose down`


---
In this example the docker compose set the container port on localhost to 3399

For connecting to MySQL:


`mysql -h 127.0.0.1 -u root -P 3399 -p`
