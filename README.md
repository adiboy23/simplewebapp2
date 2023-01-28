# simplewebapp2
This is a simple NodeJS application.
When you visit the web page running this app you will see a "Count of visits" which keeps incrementing every time a new user visits.
We are using 2 Docker containers for this :
  1. 1 container running node:alpine image
  2. 1 container running a redis (in-memory) database which keeps the count of visits.
We are using a Docker compose to containerise this application.
