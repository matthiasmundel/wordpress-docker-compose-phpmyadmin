# wordpress-docker-compose-phpmyadmin
A nice and simple WordPress setup for docker-compose tailored for web developers. Includes a blank theme and a blank plugin.
## Use
1. Navigate to the wordpress-docker-compose-phpmyadmin folder on your computer using a terminal and enter `docker-compose up -d`
2. Enter `http://localhost:8000` in your favourite web browser and follow the instructions!
## Custom domain
1. Having several docker containers running? Fed up with the standard localhost domain? Add something like `VIRTUAL_HOST: "blank.wp"` in the 'environment' section of docker-compose.yml.
2. Add this new domain to the 'hosts' file of your operating system, e.g. /private/etc/hosts on macOS: `127.0.0.1	blank.wp`
3. Open your favourite browser and navigate to `http://blank.wp:8000/`