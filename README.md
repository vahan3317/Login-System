# Login-System
login system with php ,MVC &amp; PDO ,phpmailer

If you want open project
1.clone this project
2.Create database and 2tables
 2.1 database name is reg_system
 2.2
 
 
 
 
 
 
 
      CREATE TABLE users(
          usersId int(11) PRIMARY KEY AUTO_INCREMENT NOT NULL,
          usersName varchar(128) NOT NULL,
          userEmail varchar(128) NOT NULL,
          userUid varchar(128) NOT NULL,
          usersPwd varchar(128) NOT NULL
      
      );
      
      
      CREATE TABLE pwdreset(
        pwdResetId int(11) PRIMARY KEY AUTO_INCREMENT NOT NULL,
        pwdResetEmail TEXT NOT NULL,
        pwdResetSelector TEXT NOT NULL,
        pwdResetToken TEXT NOT NULL,
        pwdResetExpires TEXT NOT NULL,
      
      );
      
      
      
      
