# LAMP STACK
# Install apache
# Update package

![image](https://user-images.githubusercontent.com/49937302/116814822-39990480-ab8d-11eb-9618-5b87bd0803ba.png)

![image](https://user-images.githubusercontent.com/49937302/116814837-49b0e400-ab8d-11eb-82db-c006d7bd4048.png)

 
# Install apache2 & verify status is running
 
![image](https://user-images.githubusercontent.com/49937302/116814828-41f13f80-ab8d-11eb-96ca-7bc1023bbe8d.png)


# allow port 80 on security group

![image](https://user-images.githubusercontent.com/49937302/116814840-4e759800-ab8d-11eb-8237-beae1a58f72c.png)

# verify there is respond from on port 80 on localhost
 
![image](https://user-images.githubusercontent.com/49937302/116814848-533a4c00-ab8d-11eb-9de3-50017617fcac.png)

# verify page is showing on the web browser
 
![image](https://user-images.githubusercontent.com/49937302/116814859-5df4e100-ab8d-11eb-9932-5dc88ca525eb.png) 
 
# Install mysql
#install mysql server

![image](https://user-images.githubusercontent.com/49937302/116814863-651bef00-ab8d-11eb-8cf2-3e47f7ce89ff.png)

# run security script
sudo mysql_secure_installation

![image](https://user-images.githubusercontent.com/49937302/116814878-7533ce80-ab8d-11eb-8722-481a28931cb3.png)

# verify can login to mysql

![image](https://user-images.githubusercontent.com/49937302/116814885-7c5adc80-ab8d-11eb-8ebf-66a788688d5d.png)

# Install PHP
#install php, libapache2-mod-php, php-mysql & verify php
 
![image](https://user-images.githubusercontent.com/49937302/116814889-81b82700-ab8d-11eb-9e76-fe51d476131e.png)

![image](https://user-images.githubusercontent.com/49937302/116814899-9dbbc880-ab8d-11eb-922c-a83489d1a4d9.png)

# Configure Virtual Host
# create directory & permission to store config for apache

![image](https://user-images.githubusercontent.com/49937302/116814907-a4e2d680-ab8d-11eb-8ead-94aa777aa386.png)

# enable virtual host and disable default sites

![image](https://user-images.githubusercontent.com/49937302/116814911-ae6c3e80-ab8d-11eb-98cb-9c6e7f7a53b7.png)

# verify no syntax error & reload apache service
 
![image](https://user-images.githubusercontent.com/49937302/116814918-b5934c80-ab8d-11eb-94c6-7320b34b0a62.png)

# create simple index.html and verify from browser

![image](https://user-images.githubusercontent.com/49937302/116814923-bd52f100-ab8d-11eb-8f2d-47e3b846d537.png)
![image](https://user-images.githubusercontent.com/49937302/116814926-c04de180-ab8d-11eb-9ce1-33eb44e521fb.png)

 
# Enable PHP on website
# change order of directory index so php will take precedence
 
![image](https://user-images.githubusercontent.com/49937302/116814934-c5ab2c00-ab8d-11eb-8f4c-07ebdf81172d.png)

# create index.php & reload apache

![image](https://user-images.githubusercontent.com/49937302/116814944-ce036700-ab8d-11eb-89b3-b5431a35dfc7.png)
![image](https://user-images.githubusercontent.com/49937302/116814946-d196ee00-ab8d-11eb-9e8f-97647e12047b.png)

 
# Remove index.php upon verify php is working as it contain info of the server

sudo rm /var/www/projectlamp/index.php

![image](https://user-images.githubusercontent.com/49937302/116814954-d9ef2900-ab8d-11eb-91de-36e577b7838c.png)






