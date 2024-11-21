# ghostBSDforDev-s
tip's dev in ghost bsd

## tip 1: install gcc and g++
with root, <br>
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
ghost@ghost#  vim /usr/local/etc/apache24/httpd.conf        <- config file <br>

![screenshot](screenshot.png)
