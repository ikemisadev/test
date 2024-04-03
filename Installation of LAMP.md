### This is a LAMP Installation Process

#### We start of with the installation of Apache
Open up the terminal

#### Then install apache with this command
```
sudo apt-get install apache2
```
#### The terminal will ask for your password then you type it in.


### Testing Apache
To make sure apache was installed properly we will now test Apache to ensure it is working properly.

1. Open up any web browser and then copy and paste the web address:

 http://localhost/

After opening the site you should see a congrats message if it was succesful.

### Install PHP

1. Return back to the terminal 

2. Copy/Paste or type the following line into Terminal and press enter:
   
```
sudo apt update 

sudo apt install php
```

3. Confirm php installation
```
php -v
```
### Install MySQL.

 1. Once again open up the Terminal and then copy/paste or type this line:
   
```
sudo apt-get install mysql-server
```
## That's a wrap of the guide. You are welcome :)