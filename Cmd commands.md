Windows CMD Commands:	

Command:					Description:								 Examples:

Basic:
cd [path]	  				- change directory                           ||	cd Documents
cd 			  				- print working directory					 || cd
dir 		  				- list the contents of the current directory || dir
echo [text]	  				- output the text							 || echo "hello world"						 
find [file]					- finds the file							 || find program.log
command /?					- find 					     || ipconfig /?
tree						- display folder structure graphically       || tree
hostname					- display host name
help [commands] 				- same as command /? but gives a bigger      || help netstat
							  description	
                              
                              
Files:
attrib	                   			- display file attributes
comp	     					- compare file contents
compact						- display/change file compression
copy/xcopy [file] [folder]  - copy files								 || copy file.txt .\Documents
diskcomp					- compare content of two floppy disks
diskcopy					- copy floppy disc to another one			
erase / del	 				- delete one or more files					 || del main.php
expand						- extract files
fc							- compare files and display the differences
mkdir						- create a new directory					 || mkdir data
move [file] [destination]   - move/rename files							 || move main.py .\Downloads						
rename [file] [new filename]- rename files								 || rename main.py calculator.py
remove [file] 				- remove a file								 || remove main.py							
rmdir 						- delete directory							 || rmdir data
type						- display content of text files 			 || type system.log

System Administration:
systeminfo 					- shows configuration of a computer and its  || systeminfo
							  operating system
tasklist 					- lists tasks, including task name and       || tasklist
							  process id (PID)
taskkill 					- ends one or more tasks					 || taskkill /PID 2343

                              
Networking:
ipconfig 					- view and control IP configuration state  	 || ipconfig
ftp   						- transfer files to a FTP server
ftype						- display file type and mapping
getmac						- display MAC address
ipconfig  					- display IP network settings
netsh						- configure/control/display network co
netstat						- display TCP/IP connections and status
nslookup					- query the DNS
pathping					- test the connection to a specific IP address
ping						- pings the network
route						- display network routing table, add 
							  static routes
telnet						- establish Telnet connection
tftp						- transfer files to a TFTP server
tracert						- trace routes similar to patchping

Batch Scripting:
call [batch filename]       - call another batch file from the current   || call calculate
							 one (also works for .cmd files)

Miscellaneous:
title [text]				- change the cmd title 						 || title hello world
prompt [text]				- used to change or reset the cmd`s prompt   || prompt $
timeout	[secs]				- wait any time								 || timeout 2