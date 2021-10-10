Linux Commands (Case Sensitive):

Basic:
pwd                ==> print the name of current directory   || Ex: pwd
whoami             ==> print the current user                || Ex: whoami
cd [directoryName] ==> enter a directory               		 || Ex: cd Music
cd ..              ==> go back to the parent directory       || Ex: cd ..
cp [file]          ==> copy file                             || Ex: cp music.mp3
ls                 ==> list all items in the current folder  || Ex: ls
clear              ==> clears the terminal                   || Ex: clear
mkdir [foldername] ==> makes folder with the specified name  || Ex: mkdir Songs
rmdir [foldername] ==> removes the specified folder          || Ex: rmdir Songs
echo [param]       ==> outputs the value of the variable	 || Ex: echo "Hi"
					   or string to stdout		             
tree 			   ==> lists the files in the current		 || Ex: tree 
					   directory in tree like format 

For sorting files:
mv [file] [newname]==> rename a file or folder  			 || Ex: mv exe txt
cat [filename]     ==> reads the specified file              || Ex: cat cmds.txt
tac [filename]     ==> reads the specified file in reverse   || Ex: tac cmds.txt
tail [file, file]  ==> reads first 10 lines of the files     || Ex: tail cmds.txt
zip [file, file]   ==> compresses the specified files        || Ex: zip files
vi [file]          ==> edit file in the terminal             || Ex: vi cmds.txt
gedit [file]       ==> edits the file in text editor         || Ex: gedit cm.txt
nano [file]        ==> edit file in nano editor              || Ex: nano cmds.txt
tar                ==> same as bzip2 						 || Ex: tar file
bzip2 -z / -d      ==> compress and decompress files with    || Ex: bzip2 -z cmds
                       the extension "bz2" respectively  
gzip               ==> same as bzip2 but compresses files    || Ex: gzip file
						with a gz extension.

Getting help:
man [command]      ==> show the manual of the command        || Ex: ls man
[command] --help   ==> similar to man but ouputs in terminal || Ex: pwd --help
apropos [word]     ==> search for the word in description    || Ex: aprpos list
					   of all commands

More advanced: 
reboot             ==> reboot the system                     || Ex: reboot
which [command]    ==> ouputs the location of the command    || Ex: which ls
su [username]      ==> impersonate as the specified user     || Ex: su root
id	 	   ==> print user and group information 	 || Ex: id
hostname 	   ==>  display or seta computer`s hostname  || Ex: hostname
uname -a           ==> show  all the information of the OS    || Ex: uname -a
exit               ==> exit the current user or the terminal || Ex: exit
shutdown -P +min   ==> shutdowns the system        			 || Ex: shutdown -P

Networking: 
ifconfig           ==> lists all the network interfaces on   || Ex: ifconfig
					   your machine 
netstat            ==> displays network connections for TCP, || Ex: netstat
					   routing tables, and a number of 
                       network interface and network 
                       protocol statistic

For listing hardware:
lscpu             ==> list CPU architecture information      || Ex: lscpu
lsusb             ==> list information about usbs            || Ex: lsusb
lsblk 		  ==> list block devices		     || Ex: lsblk
lsof		  ==> list opened files			     || Ex: lsof
lspci       	  ==> list PCI devices  	 	     || Ex: lscpi

System Administration: 
  User Management:
  who 		     ==> prints the current logged in users  || Ex: who
  users              ==> shows names of users logged in      || Ex: users
  adduser [username] ==> adds another user                   || Ex: adduser david
  useradd [username] ==> same as adduser but is not preferrd || Ex: useradd david
  deluser            ==> deletes a user                      || Ex: deluser david
  usermod [user]     ==> modify user settings & prefrences   || Ex: usermod david --shell /bin/bash
  passwd [user]      ==> change the password of the user     || Ex: passwd  
  uptime             ==> shows how long the system has been  || Ex: uptime
                         running, number logged on users and 
                         the system load averages		
  visudo 	     ==> recommended way to edit   	     || Ex: sudo visudo
  						 /etc/sudoers file
  vipw 			     ==> recommended way to edit /etc/passwd || Ex: sudo vipw
  						 file
  systemctl 		 ==> mangae all the background running   || Ex: sudo systemctl disable ssh
  						 services (daemons)
  journalctl 		 ==> see all the logs for systemctl		 || journalctl -xe
  
  Important Files:
  /etc/passwd     ==> stores information of all the users	 || cat /etc/passwd
  /etc/shadow     ==> stores the hashed version of every 	 || cat /etc/passwd
					user`s password
   
ps(Process Status)==> displays currently-running processes   || Ex: ps
pstree 			  ==> list the daemons in a tree format		 || Ex: pstree
(Process Tree)
ss(Socket Status) ==> used to dump socket statistics and	 || Ex: ss
					  displays information 