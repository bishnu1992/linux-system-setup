# linux-system-setup
Linux system setup after format


# Init


`apt update`



## Install chrome

`wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo apt-key add -`

`sudo add-apt-repository "deb http://dl.google.com/linux/chrome/deb/ stable main"`

`apt update`

`sudo apt install google-chrome-stable`

`google-chrome`


**Referance**: https://www.digitalocean.com/community/tutorials/install-chrome-on-linux-mint


## Git

apt install git


## SSH Key Generation and Auth setup

**Referance**: https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent?platform=linux

`ssh-keygen -t ed25519 -C "bishnu.nandi123@gmail.com"`

`eval "$(ssh-agent -s)"`




file name `github`

copy the text and remember the pid i.e.: `Agent pid 7931`



(Run this before accessing the github account, example cloning the private repo of it)

`ssh-add github`

`ssh -T git@github.com`



Add the public key to github.


**URL**: https://github.com/settings/keys

### Add gitconfig user.name and email
`git config --global user.name "bishnu"`

`git config --global user.email "bishnu.nandi123@gmail.com"`





## Install vi

`sudo apt install vim`
 
 
 

## Install VS Code

**Reference**: https://code.visualstudio.com/docs/setup/linux

### Few extensions for better and developmemt
- GitLens
- Code Spell Checker
