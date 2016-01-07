#ServerSideWork

#Objective
Client side mysql basic operate;

#Requirement
1. get mysql database IP,port , username, password;
2.

#Install and config
1. Mac:
Install pip: "sudo easy_install pip";
Install brew:'ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"'
Install mysql:"brew install mysql";
Install MySQLdb:"sudo pip install MySQL-python";
brew is nice, do everything for you. 
2. [link2](http://www.raspberry-projects.com/pi/software_utilities/mysql);
3. [ling3](http://raspberrywebserver.com/sql-databases/using-mysql-on-a-raspberry-pi.html);

#Content
1. change the listening IP, in Console "sudo nano /etc/mysql/my.cnf", change default ' 127.0.0.1' to "0.0.0.0", "sudo service mysql restart";
2. basic command [ling](http://www.tecmint.com/mysqladmin-commands-for-database-administration-in-linux/);
1. use pi filler(for mac) install the OS img into SD card, [headless guide](https://learn.adafruit.com/beaglebone-black-installing-operating-systems/mac-os-x)
2. For windows or other envirment, please check [link](http://www.tweaking4all.com/hardware/raspberry-pi/install-img-to-sd-card/)

#Clinet
1. "install mysql-python", [link](http://stackoverflow.com/questions/372885/how-do-i-connect-to-a-mysql-database-in-python);


#Issue
How to make own customize OS img?

#Notes
test table,"staff"
how to connect mysql, [link](http://stackoverflow.com/questions/372885/how-do-i-connect-to-a-mysql-database-in-python);
