# linux-system-setup
Linux system setup after format

# Init

apt update


## Install chrome

wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo apt-key add -

sudo add-apt-repository "deb http://dl.google.com/linux/chrome/deb/ stable main"

apt update

sudo apt install google-chrome-stable

google-chrome

Referance: https://www.digitalocean.com/community/tutorials/install-chrome-on-linux-mint


