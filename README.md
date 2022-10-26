```
install docker (ubuntu):
   sudo apt update
   sudo apt install apt-transport-https ca-certificates curl software-properties-common
   curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu `lsb_release -cs` test"
   sudo apt update
install docker (linux): 
   sudo yum update -y
   sudo yum -y install docker
   Start Docker
   sudo service docker start
   Access Docker commands in ec2-user user
   sudo usermod -a -G docker ec2-user
   sudo chmod 666 /var/run/docker.sock
   docker version
permission docker: 
   sudo usermod -aG docker `userName`
   sudo newgrp docker
install git : 
   sudo apt-get install git
install docker-compose:
   curl -L https://github.com/docker/compose/releases/download/1.21.2/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose
   chmod +x /usr/local/bin/docker-compose
install docker-compose (linux)
   sudo curl -L https://github.com/docker/compose/releases/latest/download/docker-compose-$(uname -s)-$(uname -m) -o /usr/local/bin/docker-compose

   sudo chmod +x /usr/local/bin/docker-compose

   docker-compose version
```

