
A cloud based Android Spying or Monitoring Tool, powered by NodeJS

Features
GPS Logging
Microphone Recording
View Contacts
SMS Logs
Send SMS
Call Logs
View Installed Apps
View Stub Permissions
Live Clipboard Logging
Live Notification Logging (WhatsApp, Facebook, Instagram, Gmail and more ....)
View WiFi Networks (logs previously seen)
File Explorer & Downloader
Command Queuing
Built In APK Builder
Prerequisites
Java Runtime Environment 9+
See installation for OS specifics
NodeJs
A Server
Installation on Heroku Click Here
Video Tutorial for Heroku Click Here

Installation on VPS or Server
Video Tutorial for VPS or Server Click Here

Connect to your server via SSH

Install JRE 9+

Debian, Ubuntu, Etc
sudo apt install openjdk-11-jre-headless
Fedora, Oracle, Red Hat, etc
sudo yum install java-11-openjdk-devel"
Windows
click HERE for downloads
Install NodeJS Instructions Here (If you can't figure this out, you shouldn't really be using this)

install PM2

sudo npm install pm2 -g
Clone this repository

git clone https://github.com/XploitWizer/XploitSPY.git
Now change to the server directory and run these commands

npm install <- install dependencies
pm2 start index.js <-- start the script
pm2 startup <- to run XploitSPY on startup
Default Username : admin & Default Password : password

Change the Username & Password

Stop XploitSPY pm2 stop index
Open maindb.json in a text editor
under admin
set the username as plain text
set the password as a LOWERCASE MD5 hash
save the file
run pm2 restart all
in your browser navigate to http://<SERVER IP or URL>:22533

It's recommended to run XploitSPY behind a reverse proxy such as NGINX

Happy Hacking
Disclaimer
DedSec Provides no warranty with this software and will not be responsible for any direct or indirect damage caused due to the usage of this tool.
DedSec is built for Educational Purpose. Use at your own Risk.


Modified By DedSec

Credits
Credits to D3VL for the original code base this repository is based on at L3MON
