# ghostBSDforDev-s
tip's dev in ghost bsd.

## step one
with root, <br>
ghost@ghost# pkg upgrade <br>

## tip 1: install gcc and g++
ghost@ghost# pkg install -g 'GhostBSD*-dev' <br>
ghost@ghost# pkg install gcc


## tip 2: install zsh 
ghost@ghost# pkg install zsh <br>
ghost@ghost# chsh -s /usr/local/bin/zsh   or <br>
ghost@ghost# chsh zsh  <br>
após alterar com chsh, reinicie seu sistema

## tip 3: install apache2
ghost@ghost#  pkg install apache24-2.4.62  <br>
ghost@ghost#  vim /usr/local/www/apache24/data/index.html   <- index <br>
ghost@ghost#  vim /usr/local/etc/apache24/httpd.conf        <- config file <br> <br>
![screenshot](screenshot.png)

ghost@ghost#  vim /etc/rc.conf       <- add config file !important <br>
in end file, add <br>
apache24_enable="YES"
![screenshot](screenshotone.png)
<br>
ghost@ghost# service apache24 restart

<h1>removing index of error apache2</h1>  <br>
ghost@ghost#  vim /usr/local/etc/apache24/httpd.conf   <br>
<br> in this module, remove "Indexes" options <br>

![screenshot](screenshotwo.png)
<br>ghost@ghost# service apache24 restart <br>


## tip 5: install php 8.3 
ghost@ghost# pkg install php83 <br>
ghost@ghost# php -v
