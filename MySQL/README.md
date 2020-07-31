# MySQL

### Install MySQL Sever on Ubuntu 20.04

    1. Update the apt package manager and then install mysql-server package
           ```
           $ sudo apt Update
           $ sudo apt install mysql-server
           
           ```
    2. Verify MySQL services
          ```
          $ sudo systemctl status mysql
          $ sudo systemctl stop mysql
          $ sudo systemctl start mysql
          $ sudo systemctl enable mysql
          $ sudo systemctl restart mysql

          ```
   3. Secure configuration of MySQL
         ```
         $ sudo mysql_secure_installation

         ```
   4. Login to MySQL as root user
        ```
        $sudo mysql
        ```   
