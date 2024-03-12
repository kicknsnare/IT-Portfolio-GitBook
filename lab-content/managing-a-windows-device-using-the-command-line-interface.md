# Managing a Windows Device using the Command Line Interface



### Navigating Commands

<pre class="language-powershell"><code class="lang-powershell">#Navigating Commands
#dir
dir 
dir /ah -> show all hidden files and directories
dir c:\windows\*.exe /s /b -> s matches criteria b displays only those files
<strong>#cd
</strong><strong>cd -> change directory
</strong><strong>#drives
</strong>d:, c:, e: -> changes the drive

</code></pre>



### Networking Commands

```powershell
#Networking commands
#ipconfig
ipconfig
ipconfig all
ipconfig /flushdns -> To re-register DNS names
ipconfig /displaydns
ipconfig /registerdns
#ping
ping <destination>
ping -n <number>
#hostname
hostname -> displays the name of the machine
#netstat
netstat -> show all active TCP connections 
netstat -s -p tcp -> information about a particular protocol
netstat -e -t 5 -> updated the statistics every 5 seconds
netstat -a
#nslookup
nslookup <destination>
nslookup -type=ns <destination> -> find the nameserver record 
nslookup -type=soa <destination> -> start of authority 
nslookup -type=all <destination> -> all DNS records
nslookup <IP> -> reverse resolution
nslookup -timeout=200 <destination> -> increase     limit
nslookup -debug <destination> -> Q&A with detail information
#net use -> connect computer to a shared folder/drive
net use 
net use x: \\plabwin11\c$ /persistent:yes
-yes -> the mapping will stick
-no -> the mapping will only be available in this session
net use x: /delete
#net user -> create new user, modify account related parameters
net user Louis Passw0rd /add /times:ALL -> New user
/<domain name>
net user Louis /delete

```
