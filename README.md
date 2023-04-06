# MY MOTD
 MOTD files for my servers

## Tested on Ubuntu 22.04.2 LTS

Install figlet if you will be using 00-header
```
sudo apt install figlet
```
### Installation
clone in your working directory
```
cd /etc/update-motd.d/
sudo git clone https://github.com/juvenileg/my_motd.git .
```

Ensure permissions are in place 
```
sudo chmod a+x *
```
You can test with  
```
sudo run-parts /etc/update-motd.d
```
### Other Tips

In case you cannot see the docker images, you might be using an minimized Ubuntu Image

```
sudo apt install bsdmainutils
```
