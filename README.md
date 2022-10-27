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
