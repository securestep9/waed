============================================================================
Web Application and Exploitation Distribution
============================================================================

The WAED is a lightweight linux distribution based on Debian 8. WAED is pre-configured with various real-world vulnerable web applications in a sandboxed environment using Docker containers. It includes pentesting tools that aid in finding web application vulnerabilities. The motivation behind this project is to provide an environment to learn about web application’s vulnerabilities without the hassle of dealing with complex configurations. Currently, there are around 18 vulnerable applications installed in WAED.

The majority of the applications in WAED runs in its container with a dedicated database, file system, and web server. Therefore, It’s easy to scale and deploy more applications as this distro matures. It’s easy to start, stop and restore applications without having to reinstall, which makes it a great tool for learning.


<del>The Web Application and Exploitation distribution is available from: 
ftp://gator3143.hostgator.com/waed.iso (or) https://drive.google.com/open?id=0B_GgpShRlRa2WElnQ2VTUmxlRjA
</del>

Working waed.iso download location:
https://e.pcloud.link/publink/show?code=XZ2lC0ZwrIK6o8vVAXooOYnHOdoMuti9mkV


Download
============

If you want to give WAED a try, you can download the ISO images from the following url:

    
https://e.pcloud.link/publink/show?code=XZ2lC0ZwrIK6o8vVAXooOYnHOdoMuti9mkV


Contact
=======
For information or requests, contact:

WAED Distro

https://e.pcloud.link/publink/show?code=XZ2lC0ZwrIK6o8vVAXooOYnHOdoMuti9mkV
     
     
Email: prajganesh@gmail.com

IRC: #waed on freenode

Twitter: @@rajganeshp


Quick Start
===========
1. Installation of  the latest version of WAED ISO from
    
   
2. To see available options, run "waed help"

   Example:

$ waed help

" To start apps: waed start application id : Ex: waed start 1"
" To stop apps: waed stop applicatiosn id : Ex: waed stop 1"
" To restore apps: waed restore application id : Ex: waed restore 1"
" To clean all apps:  waed clean"

Packages Details:
================
Debian OS: 8
Docker Version: 10



Vulnearable WebApps Included:
============================

1  Custom JAVA Application
2  Bodgeit Application	  (https://code.google.com/p/bodgeit)
3  JSP-Myadmin	(https://www.exploit-db.com/exploits/37152)
4  Sql Injection Series	(https://github.com/Audi-1/sqli-labs)
5  Mutillidae	(http://sourceforge.net/projects/mutillidae)
6  Wackopicko	(http://www.aldeid.com/wiki/WackoPicko)
7  Openfire	(https://www.exploit-db.com/exploits/38188)
8  Webgoat	(https://www.owasp.org/index.php/Category:OWASP_WebGoat_Project)
9  Owsap Bricks	(https://www.owasp.org/index.php/OWASP_Bricks)
10 Sql Postgres Database	
11 Sql Mysql Database	
12 Xss And Sql Series	(https://www.vulnhub.com/entry/pentester-lab-web-for-pentester)
13 Dvwa	(http://www.dvwa.co.uk)
14 MyBB	(https://www.exploit-db.com/exploits/35224)
15 Zeuscart	(https://www.exploit-db.com/exploits/36159)
16 RefBase	(https://www.exploit-db.com/exploits/38292)
17 2Moons	(https://www.exploit-db.com/exploits/37713)
18 PHPNuke	(https://www.exploit-db.com/exploits/29733)


Note:
============================

For more information about the working function of docker web application containers, please go through the waed.txt file.



Licensing and Copyright
=======================

Copyright (C) 2016-2017 

All Rights Reserved

WAED is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

WAED is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with WAED.  If not, see <http://www.gnu.org/licenses/>.

Bugs and Support
================
There is no support provided with WAED. There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR
PURPOSE. 

If you think you've found a bug, please report it at:

    https://github.com/rajganeshp/waed/issues



Command Reference 
====================
The following url contains a reference of all Docker commands supported by WAED .

    https://github.com/rajganeshp/waed/wiki


Issues
===================
If you have any problems with or questions about this image, please contact us through a GitHub issue. If the issue is related to a CVE, please check for a cve-tracker issue on the official-images repository first.


Contributing
=====================
You are invited to contribute new features, fixes, or updates, large or small; we are always thrilled to receive pull requests, and do our best to process them as fast as we can.

Before you start to code, we recommend discussing your plans through a GitHub issue, especially for more ambitious contributions. This gives other contributors a chance to point you in the right direction, give you feedback on your design, and help you find out if someone else is working on the same thing.






