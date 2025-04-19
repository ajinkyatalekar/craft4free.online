# https://craft4free.online
This repo contains the codebase for craft4free, a web platform for hosting personal minecraft java-edition servers.

## craft4free-frontend
This repo contains the react codebase for the web frontend for craft4free. This is hosted on AWS Amplify with CI/CD pipelines for dev and main branches.

## craft4free-backend
This repo contains the python codebase for the backend for craft4free. This is hosted on an oracle cloud instance. It runs traefik inside a docker container, which routes traffic to a fastapi server.
