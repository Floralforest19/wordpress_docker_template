## Configure Nginx

\$ vim ./data/nginx-conf/nginx.conf

## Define env variables
\$ cp env_example .env
\$ vim .env

## Start:
\$ docker-compose up -d
## Stop

\$ docker-compose down

## Uninstall

\$ docker-compose down --rmi all
