# mongodb-installation-and-configuration-in-servers

# Repository contents

Installation and configuration in ubuntu server

Installation and configuration in centos server

# Remote Access settingss for 2017 port
1. Go to your EC2 dashboard: https://console.aws.amazon.com/ec2/
2. Go to Instances and scroll down to see your instance’s Security Groups. Eg, it will be something like launch-wizard-4
3. Go to Netword & Security -> Security Groups -> Inbound tab -> Edit button.
4. Make a new Custom TCP on port 27017, Source: Anywhere, 0.0.0.0/0

# References
https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/
https://docs.mongodb.com/manual/tutorial/install-mongodb-on-red-hat/


