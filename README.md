# Linux
## How to deploy web application on linux
* switch to root user
* install --yum install httpd
* start		--service httpd start
* should enable the ports - http. by default only ssh is opened
* go to the path var/www/html/ and copy the application files

_Notes helpful while preforming above steps_
* sudo su #su :switch user
* ususallly linux has 3 users - root, normal user and group user
* there is a tool WinSCP to move files into linux server similar to filezilla
* httpd means apache default 
* server manager in windows - yum in lunux
* chmod -- change permission - 777

