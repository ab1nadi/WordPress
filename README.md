## Word Press Docker
This folder has an init script that should be included with the lightsail instance.  The docker-compose will store data in the volumes folder so that we can back up or migrate with it later. 

# steps in the script
- install docker snap

- clone this folder from github

- generate a data base password

- put the password in environment variables

- store the password to a file

- docker-compose up this folder.