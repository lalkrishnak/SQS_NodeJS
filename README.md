# AWS SQS NodeJS Example

Follow the instructions below on an EC2 Ubuntu instance. 
```
sudo su
apt-get update
apt-get upgrade -y
apt-get dist-upgrade -y
apt-get autoremove -y
apt-get install nodejs npm git -y
ln -s /usr/bin/nodejs /usr/bin/node
git clone https://github.com/lalkrishnak/SQS_NodeJS.git
cd SQS_NodeJS
npm install
```

***Here you will want to edit config.json with your AWS keys.***

```
node app.js
```