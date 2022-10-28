# ubuntu-svn-script
Setup SVN Server on Ubuntu Shell Script

Run the following comands to install svn on apache. 

```
sudo apt-get -y update 
sudo apt-get -y install net-tools 
sudo apt-get -y install  git
sudo git clone https://github.com/GuillenDiego/ubuntu-svn-script.git
cd ubuntu-svn-script
sudo chmod +x setupSVN.sh
sudo ./setupSVN.sh
```


```
cd /
sudo apt-get install php-pear
sudo pear channel-discover pear.geshi.org
sudo pear install geshi/geshi
sudo pear install Text_Diff
sudo pear install Archive_Tar
sudo git clone https://github.com/websvnphp/websvn.git
sudo cp -R  websvn /var/www/html
```
