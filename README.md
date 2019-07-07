-------------------------------------------------------------------------
-------------------------------------------------------------------------
-------------------------------------------------------------------------
# Node with NVM
```bash
$ curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.0/install.sh | bash
$ nvm --version
$ nvm install node
$ nvm use node
$ nvm install --lts
$ nvm use --lts
```
-------------------------------------------------------------------------
# Firefox Dev Ed with PPA
```bash
sudo add-apt-repository ppa:ubuntu-mozilla-daily/firefox-aurora
sudo apt-get update
sudo apt-get install firefox
```
-------------------------------------------------------------------------
# ANDROID SDK and tools
```bash
apt-get install android-tools-adb
```
or
```bash
# create sdk folder
export ANDROID_HOME=/opt/android-sdk-linux
sudo mkdir -p $ANDROID_HOME

# install openjdk
sudo apt-get install openjdk-8-jdk

# download android sdk
cd $ANDROID_HOME
sudo wget https://dl.google.com/android/repository/tools_r25.2.3-linux.zip
sudo unzip tools_r25.2.3-linux.zip
cd tools

# install all sdk packages
sudo ./android update sdk --no-ui

# set path
export PATH=${PATH}:$ANDROID_HOME/platform-tools:$ANDROID_HOME/tools:$ANDROID_HOME/build-tools/25.0.2/
source /etc/profile
```
-------------------------------------------------------------------------
-------------------------------------------------------------------------
-------------------------------------------------------------------------
