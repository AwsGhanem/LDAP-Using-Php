# LDAP-Using-Php
LDAP Authentication Using Php and Php_ldap.dll on Windows Server 2019 and IIS Server 

All of the Steps to Fully Configure the Windows Server 2019 and Web Server IIS are included on the PDF.
* Note that I'm using the Php-7.4 version.

[LinkedIn Post](https://www.linkedin.com/posts/aws-ghanem-621426267_ldap-configuration-activity-7197255208140173313-jmDd?utm_source=share&utm_medium=member_desktop)

# Setup the LDAP protocol 
1) Configure Acitve Directory Domain Service (Not included in the PDF)
2) Adding users (Not included in the PDF)
3) **Fully Configuring the Web Server IIS**
4) **Installing and Configuring the LDAP server "AD LDS"**
5) **Configuring PHP files and including the importing the php_ldap.dll**
6) **Importing PHP to the Web Server IIS**
7) **Constructing the code to connect to the LDAP server and start autheticating users from the AD**
8) **Handling redirection.**

> [!NOTE]
> **All of the neccessary information can be found inside the PDF from installing to configuring everything.**


> [!IMPORTANT]
> **This configuration is based on Simple-Bind, which means no security is implemented on the LDAP,**
> **in the Next version we will view the traffic on both `http` and `ldap` protocols traffic, and configure **`https`** and **`LDAPS`.****

# Stage (1): Windows Based Authentication
![image](https://github.com/AwsGhanem/LDAP-Using-Php/assets/123994471/3d6d6d37-545a-4af5-b070-a92e31ca9190)

# Stage (2): Authetication Using PHP
![image](https://github.com/AwsGhanem/LDAP-Using-Php/assets/123994471/32e90f97-73dd-4492-872a-7bf83ed47d9c)
![image](https://github.com/AwsGhanem/LDAP-Using-Php/assets/123994471/18ba0429-7e88-4ad5-94d2-d25602efd24b)


# LDAP over SSL
**Recenlty i imporoved the project, i tried to secure things as much as i can**
- **The `LDAP-v2` has https configuration added to it, and now all of the http methods are secure with a Local generated Certificate from the `AD CS`**
- **All of the Wireshark tests are also included**

![image](https://github.com/AwsGhanem/LDAP-Using-Php/assets/123994471/d8f0b302-d41f-40ed-9b45-c74dd861e4fb)


# Next Steps
**Completing the LDAPS is a major priority to wrap up the project and provide a complete sample of the LDAPS Authetication using PHP on the Windows Server 2019, fully configured from scratch.**
