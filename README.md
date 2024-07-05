# grafana-ha-poc
HA Setup for Grafana with Postgres

# Overview
This Docker Compose file sets up a highly available Grafana setup with two Grafana instances, a PostgreSQL database, and an Nginx reverse proxy to load balance between the Grafana instances. 
It uses Docker volumes for persistent data storage and a custom network for inter-service communication.
