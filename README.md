# ubuntu-svn-script
Setup SVN Server on Ubuntu Shell Script

##Install SVN 
```
sudo apt-get -y update 
sudo apt-get -y install net-tools 
sudo apt-get -y install  git
sudo git clone https://github.com/GuillenDiego/ubuntu-svn-script.git
cd ubuntu-svn-script
sudo chmod +x setupSVN.sh
sudo ./setupSVN.sh
```

## Install php 8.0
```
sudo apt install lsb-release ca-certificates apt-transport-https software-properties-common -y
sudo add-apt-repository ppa:ondrej/php
sudo apt install -y php8.0 php-xml  
cd /
sudo git clone https://github.com/websvnphp/websvn.git
sudo cp -R  websvn /var/www/html
```
