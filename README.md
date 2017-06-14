# swagger-ui-example

This project is a example of using swagger-ui locally with docker.

If you don't know about swagger, please visit: http://swagger.io/

## What you need

You just need docker with docker-compose to run.

More info: https://www.docker.com/

Nodejs is not necessary, because in docker-compose there is a image of node and it runs npm install.

## Running the project

After cloning the project, in your terminal execute:

docker-compose up

Docker-compose will download all node dependencies and runs the swagger-ui at port 9000.

Then open the browser and access: http://localhost:9000.
