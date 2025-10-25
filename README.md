# node-todo-cicd

Run these commands:


`sudo apt install nodejs`


`sudo apt install npm`


`npm install`

`node app.js`

or Run by docker compose

test


# jenkins execute shell command for webhook

docker rm -f $(docker ps -aq)
docker build . -t node-todo-new
docker run -d --name node-todo-new -p 8000:8000 node-todo-new
