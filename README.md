# Nginx-as-load-balancer

Four instances in docker containers: MongoDB, Nginx, two instances REST API on Golang.

Run by command docker-compose up -d, connections between container prescribed in docker-compose.yml

Nginx listen addr http://localhost:80, performs function load-balancer beetwen two go-apps. Examples of http-requests in test.http file. 
