magellan-docker-node-helloworld
====
This is a simple hello world web application using Node.js and Express framework built on Docker.

## Requirement
- Docker

## Usage
1. Build the Docker image: `docker build -t node-helloworld .`
2. Run the Docker image: `docker run -d -p 3000 --name helloworld node-helloworld`
3. Check the port: `docker port helloworld`
4. Access the hello world web application: `curl http://localhost:<port>/`
  - if you are using Docker Toolbox: `open http://$(docker-machine ip default):<port>/`

## License
[MIT](https://github.com/magellan-devcenter/magellan-docker-node-helloworld/blob/master/LICENSE)
