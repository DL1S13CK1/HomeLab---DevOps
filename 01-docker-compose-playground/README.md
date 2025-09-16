# Docker Compose Playground

This subproject contains my first multi-service stack using **Docker Compose**.

The goal is to experiment with defining and running multiple connected services in containers, 
practice using networks, volumes, and environment variables, and learn how to structure 
a Compose file for a real-world-like setup.

## Planned stack

- **nginx** – lightweight web server to serve static content or act as a reverse proxy  
- **postgres** – relational database used by the sample application  
- **adminer** – simple web-based UI to manage the Postgres database  
- **sample app** – a small demo application that connects to Postgres and displays data  

## Learning objectives

- Understand how to describe multi-service environments with `docker-compose.yml`  
- Practice container networking and persistent storage (volumes)  
- Use environment variables for configuration  
- Run and manage services locally as if it were a small production environment  

## Next steps

- Build and test the stack locally  
- Replace the sample app with my own simple app (e.g. Python/Flask)  
- Add a reverse proxy and healthchecks  
- Document lessons learned and improvements  
