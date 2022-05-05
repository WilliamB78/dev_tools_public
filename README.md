# Dev tools

This repository embarks a docker compose file reference to start a local web development environment based on a few key services such as :

 - Traefik
 - Portainer
 - Mailhog
 - MariaDB (or any database)

A basic knowledge of docker and docker compose is required !

Don't forget to add manually to your hosts file the urls of the services !

Or better : use hostctl

```hostctl add domains devtools portainer.localhost traefik.localhost mailhog.localhost database.localhost```
