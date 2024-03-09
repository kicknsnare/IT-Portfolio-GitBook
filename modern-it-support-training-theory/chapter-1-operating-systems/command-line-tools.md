# Command Line Tools



```powershell
#Help
<command> /?
#Clear the command line
cls
#Navigation Commands
dir
dir /ah -> show all hidden files and directories
cd <path>
################## Storage Commands ##############

#Check for errors on the drive
chkdsk /r /f
#System File Checker
sfc /scannow
#Perform formatting on a drive
format Y: /q /fs:ntfs (Y: -> letter of the drive)
#Command Line of the disk manager
diskpart

############## Copying Commands ################
copy <from-path> <to-path>
#Deployment and Image managing tool
dism


```



## Network Commands

```powershell
#Network Adapter
ipconfig
ipconfig /all
ipconfig /displaydns -> Looking for Name Resolution problems
ipconfig /flushdns -> Clears the cash
#Test for connectivity
ping <IP or page (www.page.com)>
ping <local_IP> -> See if your computer can speak the network language
ping <default_gateway> -> See if you can pass your local network
-You can ping for other computers within your local network
-You can ping to see if you can go outside your local network
#nslookup
nslookup <page>
#hostname
hostname
#Testing your TCP/IP 
netstat
#net
net user -> local accounts
net use G: \\computername\sharename ->map your local  resources

#Group Policy Commands
gpupdate /force
gpresult /r
```
