# wordpress-docker-compose-phpmyadmin
A nice and simple WordPress setup for docker-compose tailored for web developers. Includes a blank theme and a blank plugin.
## Use
Enter http://localhost:8000 in your favourite web browser and follow the instructions!
## Custom domain
Having several docker containers running? Fed up with the standard localhost domain? Add something like

VIRTUAL_HOST: "blank.wp"

in the 'environment' section of docker-compose.yml and enjoy. 
