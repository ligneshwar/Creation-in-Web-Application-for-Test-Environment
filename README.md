 # CREATION IN WEB APPLICATION FOR TEST ENVIRONMENT
  ## AIM: 
  To Creation in Web Application for Test Environment.
## PROBLEM STATEMENT:
Creating a web application for a test environment is essential to provide developers and testers with a dedicated platform to simulate, test, and validate software functionalities. The challenge lies in building an easy-to-use,   
scalable, and efficient application that supports realistic testing scenarios, automates workflows, and ensures smooth collaboration while minimizing setup and maintenance efforts.

## ALGORITHM
 ### Steps 1:
 Launch an EC2 instance in AWS using an Amazon Linux 2 AMI with a Security Group allowing HTTP and SSH traffic.
 ### Steps 2:
 Connect to the instance using SSH and install a web server like Apache
 ### Steps 3:
 Create a simple HTML file in the server's default directory with basic content for testing.
 ### Steps 4:
 Access the instance's public IP in a browser to verify the HTML page is displayed.
## COMMANDS
1. To install httpd:
```
yum install httpd -y
```
3. To enable and start httpd :
```
systemctl enable httpd
systemctl start httpd
```
4. Create a simple HTML page :
```
cd /var/www/html
```
5. Create a simple HTML page :
```
cd /var/www/html
```
6. test.php
```   
  <!DOCTYPE html>
  <html lang="en">
  <head>
     <title>MY FIRST PHP!</title>
  </head>
  </body>
  </html>
```
## OUTPUT
### REG NUMBER: 212223230113
### NAME: Ligneshwar K
1. Terminal:
 ![{C02F77AA-EBAF-4BD1-8910-20154B23EF86}](https://github.com/user-attachments/assets/816a6c2b-8ab1-435c-881c-c9cd4a05fd9c)

3. Website:
![{FFF743F7-38CB-4A63-A68B-FBCF61F0F60A}](https://github.com/user-attachments/assets/de82bc12-4706-449f-b047-8bdd1972751b)


## RESULT
Thus the web application for test environment has successfully been created and executed.


 

  

