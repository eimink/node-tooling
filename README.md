# node-tooling
Tooling container for Node.js development

Quick container to get Node.js development environment up and running with Yarn and example project.

## Startup:
Run:

docker-compose run --rm --service-ports node_dev_env

This brings you in the container shell, now you can run

yarn start

to start the project. This configuration utilizes nodemon to enable quick reloading of the server for development purposes.
