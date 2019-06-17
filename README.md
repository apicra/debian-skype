# debian-skype
INstall skype on debian

Update repo cache

Update your software repository cache

sudo apt-get update
Install gdebi

Gdebi is a simple tool for installing .deb packages and it also supports automatic resolving of dependencies.

sudo apt-get install gdebi
Download Skype for Linux

Now download latest skype package using wget command

wget https://repo.skype.com/latest/skypeforlinux-64.deb
Install Skype for Linux

Install the downloaded .deb package using gdebi

sudo gdebi skypeforlinux-64.deb

That’s It! Now you can start using Skype by typing skypeforlinux in terminal or from the applications menu
