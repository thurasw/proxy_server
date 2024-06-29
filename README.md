# Simple Reverse Proxy using Traefik

Uses docker compose to setup a simple reverse proxy server with Traefik.
Traefik allows auto discovery of new services/websites deployed on docker containers.

This allows services/websites to be added and removed from the proxy without the need to specify them in the proxy config or any restarts/downtime.
