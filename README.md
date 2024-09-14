```
install docker (ubuntu):
   sudo apt update
   sudo apt remove docker docker-engine docker.io containerd runc
   sudo apt install apt-transport-https ca-certificates curl software-properties-common
   curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg
   echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
   sudo apt update
   sudo apt install docker-ce docker-ce-cli containerd.io
   sudo usermod -aG docker $USER

install docker-compose (ubuntu)
   sudo apt update
   sudo apt install curl jq
   sudo curl -L "https://github.com/docker/compose/releases/latest/download/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
   sudo chmod +x /usr/local/bin/docker-compose

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

install git ( ubuntu)
   sudo apt update
   sudo apt install git
gerb creob 
   grep CRON /var/log/syslog
```

