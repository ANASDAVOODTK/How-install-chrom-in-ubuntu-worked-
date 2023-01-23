# How-install-chrom-in-ubuntu-worked



I tried to replicate and had same issues as you. But an alternative approach worked for me. You may try that, preferably on fresh ubuntu instance.

install pre-requsits

sudo apt update
sudo apt install unzip libnss3 python3-pip
install driver for chrome 83

cd /tmp/
sudo wget https://chromedriver.storage.googleapis.com/83.0.4103.39/chromedriver_linux64.zip
sudo unzip chromedriver_linux64.zip
sudo mv chromedriver /usr/bin/chromedriver
chromedriver --version
install google-chrome-stable current version (83)

wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo apt install ./google-chrome-stable_current_amd64.deb
check installation

google-chrome-stable --version
