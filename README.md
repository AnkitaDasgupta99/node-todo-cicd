# node-todo-cicd

Run these commands:


`sudo apt install nodejs`


`sudo apt install npm`


`sudo npm install`

`node app.js`

or Run by docker compose

test


# jenkins execute shell command for webhook

docker rm -f $(docker ps -aq)
docker build . -t node-todo-new
docker run -d --name node-todo-new -p 8000:8000 node-todo-new

# all end to end command for ec2 instance

1  sudo apt update
    2  sudo apt install -y curl fontconfig openjdk-17-jre
    3  echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc]   https://pkg.jenkins.io/debian binary/ | sudo tee   /etc/apt/sources.list.d/jenkins.list > /dev/null
    4  sudo apt update
    5  sudo apt install jenkins -y
    6  sudo systemctl start jenkins
    7  java -version
    8  curl -fsSL https://pkg.jenkins.io/debian/jenkins.io-2023.key | sudo tee   /usr/share/keyrings/jenkins-keyring.asc > /dev/null
    9  echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc]   https://pkg.jenkins.io/debian binary/ | sudo tee   /etc/apt/sources.list.d/jenkins.list > /dev/null
   10  sudo apt update
   11  sudo apt install jenkins -y
   12  sudo systemctl start jenkins
   13  sudo systemctl enable jenkins
   14  sudo systemctl status jenkins
   15  sudo ufw allow 8080
   16  sudo ufw status
   17  sudo cat /var/lib/jenkins/secrets/initialAdminPassword
   18  ssh-keygen
   19  cd .ssh
   20  ls
   21  cat id_rsa
   22  cat id_ed25519
   23  cat id_ed25519.pub
   24  cat id_ed25519
   25  clear
   26  cd /var/lib/jenkins/workspace/jenkins-todo-app
   27  ls
   28  sudo apt install nodejs
   29  sudo apt install npm
   30  sudo npm install
   31  node app.js
   32  sudo rm Dockerfile
   33  sudo apt install docker.io
   34  vim dockerfile
   35  sudo vi dockerfile
   36  ls
   37  sudo usermod -a -G docker $USER
   38  docker build . -t node-app
   39  sudo reboot
   40  docker build . -t node-app
   41  cd /var/lib/jenkins/workspace/jenkins-todo-app
   42  docker build . -t node-app
   43  docker run -d --name node-todo-app -p 8000:8000 todo-node-app
   44  docker run -d --name node-app -p 8000:8000 node-app
   45  docker ps
   46* 
   47  sudo chmod 777 /var/lib/jenkins/workspace/jenkins-todo-app
   48  sudo usermod -a -G docker jenkins
   49  systemctl restart jenkins
   50  sudo systemctl restart jenkins
   51  docker ps
   52  docker kill 2322b567459b
   53  cd /var/lib/jenkins/workspace/jenkins-todo-app
   54  docker ps -a
   55  docker kill 322b567459b
   56  docker kill 2322b567459b
   57  docker rm node-todo
   58  docker ps -a
   59  docker rm
   60  docker ps -a
