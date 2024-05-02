# LDAP-Using-Php
LDAP Authentication Using Php and Php_ldap.dll on Windows Server 2019 and IIS Server 

All of the Steps to Fully Configure the Windows Server 2019 and Web Server IIS are included on the PDF.
* Note that I'm using the Php-7.4 version

# Setup the LDAP protocol 
1) Configure Acitve Directory Domain Service (Not included in the PDF)
2) Adding users (Not included in the PDF)
3) **Fully Configuring the Web Server IIS**
4) **Installing and Configuring the LDAP server "AD LDS"**
5) **Configuring PHP files and including the importing the php_ldap.dll**
6) **Importing PHP to the Web Server IIS**
7) **Constructing the code to connect to the LDAP server and start autheticating users from the AD**
8) **Handling redirection**

> [!NOTE]
> **All of the neccessary information can be found inside the PDF from installing to configuring everything**


> [!IMPORTANT]
> **This configuration is based on Simple-Bind, which means no security is implemented on the LDAP,**
> **in the Next version we will view the traffic on both `http` and `ldap` protocols traffic, and configure **`https`** and **`LDAPS`****

  
