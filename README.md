# OSA Consulting Tech  <img src="./head/logo.jpeg" align="left" height="48" width="48" > </br>

## MySQL_server_Installation
Before going to work with mysql server, make two group based on Mac user and Windows user. 
## Server Installation For Windows 
### Setp 1: Download XAMPP
1. Click <a href="https://www.apachefriends.org/download.html">here </a> to download and install XAMPP from Apache webside. 
2. Double click on the downloaded file and follow all the instraction to install.
<i>Note </i>: Keep all the setting default.

### Setp 2: Setup Environment variable

3. Go to your This PC C Driver and find find XAMPP directory
4. Find mysql directory from the XAMPP directory and copy the path.
5. Right click on This PC --> Properties --> Advanced System Setting --> Environment --> New (under System variables) --> In pop up input box Variable Name MYSQL and in value input box enter the path that you copy. exampel: C:\xampp\mysql 
6. Now double click on path under User variable --> click on new from top right corner --> enter %MYSQL%\bin  --> press ok --> ok and close it.
### Setp 3: Run MySql server
7. open XAMPP and next to mysql, click on start--> You will see the background color of mysql will change to blue
8. Open CMD - run the following command: mysql.exe –h localhost –u root -p
9. It will ask you to enter password: 
10. Press enter <i>Note</i>: There is no password required
11. Run this command to see all the default databases for confirming that server is working: show databases;

# MySQL Installation for Mac
We will install MAMP for Mac, it is easier to install on Mac and work exaxtly same as XAMPP in window. 

### Step 1: Download MAMP
1. Click <a href="https://www.mamp.info/en/downloads/">here </a> and click on download MAMP for Mac.
### Step 2: Install MAMP in Mac
2. Double click on the downloaded file and follow all the instraction to install.
<i>Note </i>: Keep all the setting default.

### Step 3: For Mac, no need to setup environment

### Setp 4: Run MySql server
3. Open MAMP and start the server from top right corner button --> You will see the background color of button will change to green
4. Open Terminal and run the following command: /Applications/MAMP/Library/bin/mysql --host=localhost -uroot -proot
5. It will ask you to enter password: 
6. Press enter <i>Note</i>: There is no password required
7. Run this command to see all the default databases for confirming that server is working: show databases;

