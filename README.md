# Pi-Hole docker compose with ipvlan network
* Simple docker-compose.yml file
* Creates Pi-Hole container and ipvlan network
* Run on server and avoid clashes with other services

Note:
Your host server will not be able to use Pi-Hole for DNS as the host network is isolated from the ipvlan network
