# First Notes

If you install a server operating system you have to make it domain controller to be a domaing controller and then you have to put Active Directory to make it domain controller



Active Directory

I need a windows server 2019 can be,&#x20;

* Server Manager&#x20;
* Manage
* Add roles and features
* Server Roles -> Active Directory Domain Services
* Install
* Promote this server to a Domain Controller
* Deployment Configuration -> Add a new forest



* Tools-> Active Directory Users and Computers
* Users -> create new user&#x20;
* Properties -> Member of ->Domain Admins -> Apply

How to add a computer to a domain?

* Access work and school (if it works)
* System -> Scroll down -> Advanced System Settings
* Computer Name -> Change -> Domain
* If you get an error go to your server and OPEN cmd -> ipconfig /all (grap the IP)
* Open Network & Internet Setting (Internet Logo)
* Change Adapter Options -> Ethernet->Properties
* IPv4 -> Properties -> Use the following DNS settings



```powershell
#See if im logged in the domain
whoami /fqdn
```



## Administrative Tools

* Apps and features
* Optional Features
* Add features
* RSAT Active Directory
