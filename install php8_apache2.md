Install apache2
```
#!/bin/bash
sudo apt-get -y update
sudo apt-get install -y \
  apache2
sudo service apache2 restart
```

Install Git and clone repo
```
sudo apt-get -y install net-tools 
sudo apt-get -y install  git
sudo git clone https://github.com/websvnphp/websvn.git
sudo cp -R  websvn /var/www/html
```
Install php pear
```
sudo apt-get -y install php-pear
```

install php second option
```
sudo apt install lsb-release ca-certificates apt-transport-https software-properties-common -y
sudo add-apt-repository ppa:ondrej/php
sudo apt install php8.0

```
