# ReactJs, Docker and Microservices

To run the project (development mode):

1. Install Docker CE for Mac or Windows (http://docker.com)

1. Install ReactJs CLI: `npx create-react-app`

1. Run `npm install` in ./client

1. Run `ng build` in ./client

1. Run `npm install` in ./server/microservices/node

1. Move back to the project root

1. Run `docker-compose build`

1. Run `docker-compose up`

1. Navigate to http://localhost

<!-- 1. To see your container CPU utilization, memory, etc. visit the
cAdvisor URL: http://localhost:8080 -->