# install-android
Install VirtualBox for genymotion
deb https://download.virtualbox.org/virtualbox/debian <mydist> contrib
Add the following line to your /etc/apt/sources.list. According to your distribution, replace '<mydist>' with 'artful', 'zesty', 'yakkety', 'xenial', 'trusty', 'stretch', 'jessie', or 'wheezy' (older versions of VirtualBox supported different distributions):
sudo apt-key add oracle_vbox_2016.asc
or
wget -q https://www.virtualbox.org/download/oracle_vbox_2016.asc -O- | sudo apt-key add -
sudo apt-get update
sudo apt-get install virtualbox-5.2 (lastes 5.2 or replace 5.1 for lasetes 5.1)

ref:https://www.virtualbox.org/wiki/Linux_Downloads
install android studio
apt-get install lib32stdc++6

download android studio at https://developer.android.com/studio/install
unzip android-studio-ide-162.3934792-linux.zip 
mv android-studio /opt/
/opt/android-studio/bin/studio.sh

install genymotion
chmod +x <Genymotion installer path>/genymotion-<version>_<arch>.bin
cd <Genymotion installer path>
./genymotion-<version>_<arch>.bin -d <Genymotion installer path>
cd <Genymotion installer path>
./genymotion
ref: https://docs.genymotion.com/latest/Content/01_Get_Started/Installation.htm
