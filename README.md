# Reverse Proxy and Monitoring with Traefik 

# CI/CD pipeline built and deployed with Docker Compose

Runs containers for Traefik, Jenkins, Nexus Repository, Gogs (self-hosted Git service) and PostgreSQL (dependency for Gogs)

To deploy containers locally, run `docker-compose up -d` in the root folder.

Note: This has only been tested on Windows, with Ubuntu 20.04 on WSL2

## Screenshots

### Traefik at traefik.localhost

![traefik-1](screenshots/traefik-1.png)
![traefik-2](screenshots/traefik-2.png)

### Nexus Repository at nexus.localhost

![nexus-1](screenshots/nexus-1.png)

### Jenkins at jenkins.localhost

![jenkins-1](screenshots/jenkins-1.png)

### Gogs at git.localhost

![gogs-1](screenshots/gogs-1.png)
