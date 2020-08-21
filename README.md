# docker-node-js

Dockerfile builds the image\
package-lock.json must be added to ensure github CI process works

## Commands
`sudo docker build -t pi/docker-node-js . [space]`\
`sudo docker images`\
`sudo docker run -p 49160:8080 -d pi/docker-node-js`\
`sudo docker rmi ce5e3c31913b`\
`sudo docker ps`\
`sudo docker ps -a`\
`sudo docker stop 4ad508e8a99b`

## Wiki
Install supervisor: `npm install -g supervisor`
https://mochajs.org/ \
https://registry.hub.docker.com/search?q=&type=image&architecture=arm%2Carm64&image_filter=official \
https://nodejs.org/de/docs/guides/nodejs-docker-webapp/ \
https://docs.npmjs.com/cli/ci\ \
https://github.com/goldbergyoni/javascript-testing-best-practices/ \
npm alias: https://stackoverflow.com/questions/51358235/difference-between-npm-start-and-npm-run-start
