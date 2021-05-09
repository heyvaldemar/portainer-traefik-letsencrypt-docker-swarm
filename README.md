# Portainer with Let's Encrypt in a Docker Swarm

Configure Traefik before applying the configuration.

Traefik configuration: https://github.com/heyValdemar/traefik-letsencrypt-docker-swarm

Deploy Portainer in a Docker Swarm using the command:

`docker stack deploy -c portainer-traefik-letsencrypt-docker-swarm.yml portainer`
