# Basic_LINUX_Tutorial_Document
💖💖Welcome To Basic Linux Tutorial 💖💖

# About LINUX

  🟢 Linux is an open-source  operating  system  inspired by UNIX.
  Linux  is just  a kernel  and Linux distribution  makes  it a usable operating  systems, preferred os for computers, servers, mainframes, mobile  devices and embedded  devices.
 
 ⏰ Father of Linux operating  system: Linus Torvalds.
# 📌Why we use Linux?:
 
  🟢 The main benefits  are its offers a free  operating  system, you do not have to spend hundreds  of  dollars  to get the OS like Windows. 
  
Bing open source  it undefined the source code , the Linux  operating  system  now pff millions  of programs  appl to choose  from  most  of them are free.
    
  🟢 The once you have  Linux  installed  you no longer needed an anti-virus  because Linux source  system  more so there  is a global development community constantly  looking  at ways  to enhance  its security  with  each upgrade the OS becomes more secure  and robust. 

  🟢 Linux  is the OS  of choice for server environments  due to ist stability  and reliability 
   Mega companies like Amazon,  Facebook  and Google  used Linux  for their  service. 

A Linux based server could run non-stop without a reboot for years on end
  
     
  
#  📌How Different is Linux whene Compared to UNIX 📗:
 
  🐱‍👤UNIX  is a propriety operating  system  from Bell Laboratories the open Group  holds the UNIX  trademark & manage thr UNIX trademark  licencesing program. 

Companies have their own licencesed UNIX  : 

       IBM(AIX)
       HP(HP- UX)
       Apple (OSX)
  
  🐱‍👤  Linux  is free , open source  and instanded as a non-propriety operating system for the masses.
  
  LINUX  is a clone of Unix , written from Scratch  by linus Tarvalds & his team.
 
 
 #  📌What is Linux kernel?🐱‍🚀:
 
 The Linux kernel is a low-level system software whose main role is to manage hardware resources for the user. 

 It is the core of any os & it is responsible for translating the user commands into equivalent language understood by the computer hardware
 
 #  📌What is Shell?🐱‍🚀:
 
 The shell is a program that takes commands from  keyboard and passes them to the operating system for performing 
 
Or, the shell is the Linux command line interpretor it provides an interface between the user and the take kernel and executes program called commands
 
 #  📌What is BASH?🐱‍🚀:
 
 BASH is short for Bourn and again shell . It's replacement to the original shell

 BASH  is the  free  and enhanced version of the Bourn e shell distributed with Linux and GNU operating systems.
 
 
 #  📌What are the advantage of Linux being open-source?🐱‍🚀:
 
 Being open-source linux gives users access to the source code open source allows user to distribute  the software, including source the code freely to anyone  interested. 
 
 It allows users to add features,  debug and correct errors in the original  source code.
 
 When the source code has been improved  it can be freely redistributed (open-source collaboration)
 
 #  📌Explain the Functionality of root user🐱‍🚀:
 
The root user is similar to a superuser  to a system administrator 

Root user has ultimate control and access to all file/directories in the system 

Another advantage: restricted program can be executed from the terminal by using the root account
 
 
 #  📌What is CLI?🐱‍🚀:
 
 CLI  stands for command line interface. This interface allows users to type declarative command  to instruct computer to perform operations.
 
 Linux CLI is called terminal and command will be interpreby the shell.

 Advantage :
       Multiple steps can be executed by specifying a single command
 #  📌What is GUI?🐱‍🚀:
 
 GUI Stands for graphical interfaces and makes the system attractive.
 
 Users who find it difficult to remember commands. Can use the GUI.
 
 GUI allows the users to negative/ access files by clicking on images and icons.

 
 #  📌What is Swap Space?🐱‍🚀:
  
  Swap space is a certain amount of space used by linux to temporarily hold active programs.
  
  This happens when RAM does not have enough memory  to hold all programs that are being executed.
 
  #  📌What are the kind of permissions available in Linux🐱‍🚀:
 
 There are basically 3 levels of file / directory  permissions in linux. 

    Read :users  only  read the files or list the directory content 

    Write : users  can only  write information to the file and creat files/ sub- directories in a directory. 

    Execute : user can run the file or lookup a spec file within a directory
 
 #  📌Users and group in Linux🐱‍🚀:
 
 🟢 A user is an entity,  in a Linux operating system,  that can manipulate and perform several other operation. 
 
   Users  are accounts that can be used to login into a system.
 🟢 Each users  us identified by a unique identification number or UID  by the system 
 
  🐱‍ All the information of users in a system are stored in file -
  
           /etc/passwd
  
  🐱‍The hashed passwords for users  are stored in file -
           
           /etc/shadow
   
   
  🟢 There are three types  of user in linux- 
  
         root , regular , service,
   
   
  1. The root user Account: 
   
 🔗 This is main user account  in linux system. 
    
 🔗It is  automatically created during the installation.
    
 🔗It has the highest privilege in system 
    
 🔗It can do any administrative work and can access any service .
    
 🔗It should not be used for routin activities 
    
 🔗It cannot be deleted. But if require it can be disabled

 2. the regular user account:
    
🔗This is the normal user account during the installation,  one regular user account is created.

🔗After the installation we can creat as many regular user account as we need .

🔗This  account has moderate privilege .

🔗This account is intended for roùtin works it can access only those file and services for whiche it is authorized. As per requirement it can disable or deleted
   
  3.The service account: 
   
🔗Service account are created by installation packages when they are installed these account are used by Service  to run processes and execute functions


🟢  groups :

🔗User  can be listed  in different groups. Group allow us to set permissions on the group level  instead of setting the permissions  on individual  level


 
 #  Basic Commands & operation in Kali Linux📸🐱

🎭 --help  :  It will print the general  syntax  of the command   along with the various options that can be used with the command as well as given a brief description about each option.
     
       [commandName] --help
       

   #  $who 🐱‍👤 
   Used to get information about  currently loogd in user on to systems. It can also show the current run level,  time of the last systems boot and more.
   
     who
   
   #  $whoami 🐱‍👤
   Used to display the username of the current user when this command is invoked.
     
      whoami
   
   
   #  $users 🐱‍👤
   Used to show the user names of users currently logged in to the current host
   
       users
   #  $uname 🐱‍👤
   To display the information about the system (Os)
   
       uname
   #  $pwd 🐱‍👤
   Prints the current working directory path.
   
       pwd
   #  $ls 🐱‍👤
   Used to list files or directories within the file system and show detailed information about them
   
      ls
      
   Example : 
    
   1. Open Last Edited File Using ls -t

           ls -t
    
  2. Display One File Per Line Using ls -1
    
          ls -1
     
   3. Display All Information About Files/Directories Using ls -l
    
          ls -l
     
   4. Display File Size in Human Readable Format Using ls -lh
       
          ls -lh
       
   5. Display Directory Information Using ls -ld
     
          ls -ld
       
   6. Order Files Based on Last Modified Time Using ls -lt
    
          ls -lt
       
   7. Order Files Based on Last Modified Time (In Reverse Order) Using ls -ltr
    
          ls -ltr
       
   8. Display Hidden Files Using ls -a (or) ls -A
    
          ls -a
       
   9. Display Files Recursively Using ls -R
    
          ls -R
       
   10. Display File Inode Number Using ls -i
    
            ls -i
      
   11. Hide Control Characters Using ls -q
    
            ls -q
      
   12. Display File UID and GID Using ls -n
     
           ls -n
      
   13. Visual Classification of Files With Special Characters Using ls -F
    
           ls -F
      
   14. Visual Classification of Files With Colors Using  ls –color=auto
      
           ls –color=auto
   15. Get a full list of hidden files .information about the user presentation,  size of the file and date and tjme of modifications Using  ls –la
    
            ls -la
    
   #  $cd 🐱‍👤
   Used yo chnage current working  directory
   
  syntax:  
    
      cd [directory_name]
  
  Example :
  
   1.Change directory to the root directory: 
           
           cd /
   
   2.Change directory to the home directory: 
    
         cd ~
         
   3.Move to the parent directory of current directory
      
         cd ..
     
   4. Navigate to a directory with white spaces
      
           cd "dir name"
        
    
   #  $man 🐱‍👤
   Used to display the user manual of any command that we can run on the terminal
   
   syntax: 
   
      man [option] [section number] [command name]
         
         
   🔗option – the search result output.
   
   🔗section number – the section in which to look for the man page.
   
   🔗command name – the name of the command which man page you want to see.
   
   Example: 
   
   💻Look for man Pages :
   
The -f option displays all man pages that match the specified command name and states the sections in which the given command is present.

     man -f sleep
       
Display man Pages From Specific Sections:
 
     man 3 sleep  
     
   #  $mkdir 🐱‍👤
   Allows to user to creat or make new dirwctoin the current working director
   
   syntax: 
   
           mkdir [options...] [directories_name]
    
  Example :
    
  1.To displays a message for every directory created
    
          mkdir -v [directories]
           
          
   #  $rmdir [dir_name] 🐱‍👤
   Used yo remove emty directories from the file system
   
        rmdir mydir1
      
   #  $rm [dir_name] -rf 🐱‍👤
   Use to remove non' empty directories  from the file system
        
        rmdir mydir1 -rf
   
   #  $clear 🐱‍👤
   Used  to clear the terminal screen
   
        clear
        
   #  $cp 🐱‍👤
   Used to coppy files or group of  files or directory 
   
  Syntax :
   
   1. Copy Source file to Destination file -
           
           cp [Source] [Destination]

   2. Copy Source file to Destination directory -
         
           cp [Source] [Directory]
  
   3. Copy multiple Sources(files) to Directory -
        
           cp [Source-1] [Source-2] [Source-3] [Source-n] [Directory]
            
   
   #  $mv 🐱‍👤
   Used to move one or more files or directory from one placed  to another place in the file system
   
   Syntax: 
   
          mv [source] [destination]
          
   It also used  to rename file name 
   
   To rename a file need to specify a single file  as a source  and a single file as a destination  target . Where destination should not exist  any directories name

 #  Important Commands & Operations📸🐱


   #  $date 🐱‍👤
  Used to print out or display the system dare and time 
   
   EXAMPLE :
     
   1. date with no option displau current date.
          
          date
          
   2. -u Option: Displays the time in GMT(Greenwich Mean Time)/UTC(Coordinated Universal Time )time zone. 
      
          date -u
          
   #  $sudo date --set 🐱‍👤
   Used to set date and time nof the system
    
        sudo date --set '11 feb 2023 00:01'
   
   #  $cal 🐱‍👤
   Used to see the calendar of a specific month or a whole year
   
   Syntax: 

         cal  [ month ] [year]
         
   Example : 
   
   1.calendar of the complete current year with the current date highlighted using cal -y
         
            cal -y
          
   2. Shows calendar of selected month and year. 
 
            cal  [ month ] [year]
   
   3. Shows the whole calendar of the year. 
    
            cal [year]
           
   #  $figlet/toilet 🐱‍👤
   The command makes turns ordinary terminal text into big fancy letters or creating ASCII text banners
   
   Example :
   
 1.Transform as a banner or large text using figlet
     
       figlet -c Sastik Kumar
      
 2. The toilet command is also used to transform text to large ASCII characters
     
       toilet kali linux
        
   #  $factor 🐱‍👤
   Used to print the prime factors of the given numbers
   
   Syntax:

           factor [NUMBER]

   #  $ps 🐱‍👤
   Used to list the currently running  processes and their PIDs along with some other information depends on different options.
   
   Syntax: 
   
         ps [options]
   
   Example :
        
           ps
   
    1. View all processes associated with this terminal : 
 
           ps -T
           
    2.  View all the running processes :  
          
          ps - r

   #  $top 🐱‍👤
   Used to print all process and an overview of all the processes that are running  in linux systems
   
        top
        
   #  $kill /pid 🐱‍👤
   Used to show a real-time view of running processes in linux and display kernel-managed the PID
      
           kill [pid]
      
   Example :
   
     1. To display all the available signals you can use below command option-
        
            kill -l
      
   
   #  $dpkg 🐱‍👤
   Used to interact with packages on our system the dpkg command  provides  a long list option to customise the data we received while analysing our network. 
   
   Example : 
   
    1. To view and list all the installed packages, use the “-l” option along with the command.
     
            dpkg -l
           
     2. To view a specific package installed or not use the option “-l” along with package-name. For example
     
            dpkg -l [package_name]
           
     3.Check a Package is installed or not
     
             dpkg -s
     
     4. Check the location of Packages installed
     
            dpkg -L [package_name]
           
     5. Replace available Package information
          
            dpkg –-update-avail [package_name]
          
     6.Forget Uninstalled and Unavailable Packages
     
             dpkg --forget-old-unavail
     
   
   #  $vlc 🐱‍👤
   To run VLC media player  using command line replace source with path to the file to be played
       
       vlc [source]
       
   #  $display 🐱‍👤
   Use it to display images sequence on any x server
   
       display [source]
   
   #  $sudo shatdown 🐱‍👤
   Used to shutdown the in a safe way you can shutdown the machine immediately or schedule a shutdown using 24 hours format
   
   Syntax :
     
          shutdown [OPTIONS] [TIME] [MESSAGE]
          
    Example :
           
           sudo shutdown now
           
   1. Make shutdown power-off machine
      
          shutdown -P
            
   2. reboot using shutdown
       
          shutdown -r
            
   3.cancel a scheduled shutdown
       
          sudo shutdown -c
   
#  Text Logs Related commands in Linux📸🐱


   #  $touch 🐱‍👤
   The touch command is a standard command used in LINUX/UNIX OS which is used to craet , chnage and modify timestamp of a file
   
   #  $echo 🐱‍👤
   Used to display line of text / string that are passed as an argument
   
   #  $fight 🐱‍👤
   Used for highlight text text saving file
   
   #  $ifconfig 🐱‍👤
   Used for ip information savin a text file
   
   #  $cat 🐱‍👤
   Used to display text file on screen  read text file   creat a new text file file concatenation...etc
   
   #  $head 🐱‍👤
   Used to print top n nunber of data of the given input
   
   #  $tail 🐱‍👤
   Used to print last n number of data of the given input
   
   #  $more 🐱‍👤
   Used to view the text files  in the command prompt displaying one screen at a time in case the file is large
   
   #  $less 🐱‍👤
   Used to read the contents of a text file one page at a time .it is faster acces because if file is large if doesn't access the complete file but access it page by page
   
   #  $nano 🐱‍👤
   To creat and open a new file in nano text editor
   
   #  $vim 🐱‍👤
   To creat and some options to do a new file in vim text editor
   
   
   
   
   
   The first thing to write in a vim editor is to press i.
 And at the end you have to type  : wq!
 Where w for save and 
             q for quit vim
   
  

# Gettings System Info in Linux📸🐱


   #  $df 🐱‍👤
   Used to display information related to fine system about total space and available space
   
   #  $free 🐱‍👤
   Used to display summary about the total amount of the physical and swap memory as well as the free and used memory
   
   #  $du 🐱‍👤
   Short for disk usage is use to estimate file space usage the do command can be consuming excessive amount of space on hard disk drive
   
   #  $cat/proc/cpuinfo 🐱‍👤
   Display  what type of processor your system is running including the number of cpu's  present. Provides each process with an identifying number
   
   #  $lscpu 🐱‍👤
   Used to display information about the cpu architecture
   
   #  $lsblk 🐱‍👤
   Used to display details about block devices and these block devices are basically those files that represent devices connected to the pc
   
   #  $lsusb 🐱‍👤
   Used to display the information about usb buses and the devices connected to them
   
   #  $lspci 🐱‍👤
   Used to displays information about each PCI bus on the system. This includes information about the devices connected to the PCI subsystem
   
   #  $dmicode 🐱‍👤
   Used to reads the system DMI table to display hardware and BIOS information of the server
   
   #  $lsb -release 🐱‍👤
   Utility display LSB (Linux Standard Base) information about the Linux distribution
   
   
#  Users and Groups in Linux📸🐱


   #  $adduser [user_name]🐱‍👤
   Used to add a new user to your current Linux  machine. It allows us to modify the configuration of the user which is to be created
   
   
   #  $cat /etc/passwd🐱‍👤
   Used to display a plan text -based  database that contains information for all user account on the system giving  for each account some usefull information like user id group id home directory shell and more
   
   #  $userdel [user_name]🐱‍👤
   Used to delete a user account and related files. Basically modifies the system account files , deleting all the entries which refer to the  username login
   
   #  $groupadd [gp_name]🐱‍👤
  Group add command creat a new group  account using the values specified on the command line and the default values feom the system
   
   #  $cat /etc/group 🐱‍👤
   Used to display a plan text-file that contains a list of groups  and members belonging  to each group on the system
   
   #  $groupdel [gp_name]  🐱‍👤
   Used to delete  all entries related to a group in the system
   
   #  $passwd [user_name]🐱‍👤
   Used to chnage passwords for user accounts
   
   
   
   
  #  Networking Command in Linux📸🐱


   #  $ifconfig 🐱‍👤
   Used to assign an address to a network interface and to configure  or display  the current network interface configuration information
   
   For display the current network interface configuration information
   
   For assign an ip address and netmask address
   
   #  $ping 🐱‍👤
   Used to check the network connectivity  between host and server. 
This command takes as input the ip or the URL and sends a data packet to the specified  address with the message " PING" and get a response from the server/host this time is recorded which is called latency 

 First ping low latency means fatser connection
   
   #  $nslookup 🐱‍👤
   Used for DNS (Domain Name System) lookup oper also used to find the ip address of a particular domain name or find out the domain name of a particular ip address
   
   
   #  $host 🐱‍👤
   Used for getting information from the DNS server also used to troubleshoot DNS-related problems
   
   #  $arp -e 🐱‍👤
   The arp stands for " Address Resolution Protocol" it makes  changes in the kernel's table which contains the arp Address 
   
  It communicates with the IPV4  network and resolves the  ip address of any other machines  into the physical  address which is known as the MAC(Media Access control) address
   
   #  $hostname 🐱‍👤
   Hostname  is used to display the system DNS name and display or set its host name or NIS(Network Information System) domain name.
   
   
   #  $netstate 🐱‍👤
   Used for monitoring network connections both incoming and outgoing as well as  viewing tables , interfaces  stastic...etc
   
    To show both list ening and non- listening sockets
    To list all TCP ports
    To list all udp ports
    To list the statistics  for all ports
    To display the PID and programm names
    
    
   #  $ip 🐱‍👤
   Stands for internet protocol. Used to show or manipulate. Routing devices, and tunnels. 
  It is much more powerful with more functions and facilities than ifconfig command
   
   
   Used to much more powerful with more functions and facilities than ifconfig command.
   
 Used to show all ip address associated an all network devices
 
 Used to show of an particular interface
 
 Itis used to display link layers information
 
 This link option when used with -s option  tp show the statistics of the various network
 
 This command helps you to see the rout packets your network will take as set in your table
 
 This is used to assign an ip address to an interface
 
 This is used to delete an an assignment ip address to an interface.
 
 This option enables a network inter face.
 
 This command  can monitor and displays the state of devices address and routes continuosly
 
   #  $ss 🐱‍👤
  Used to show network statistics. Ss is faster version of netstate command .
Ss is essential for gathering network information  and troubleshooting network issues
   
   #  $dig 🐱‍👤
   Dig command stands for domain information grouper basically used by network administrators used for verifying and troubleshooting DNS  problems and to perform  🎭  DNS lookups. Also ised for retrieving information about DNS lookups.
 Also used for retrieveing information about DNS name servers
   
   #  $ssh 🐱‍👤
   SSH stand for "Secure Shell" It is a protocol used to security connect to a remote server/system. Ssh is secure in the sense that it transfers  the date in encrypted from between the host and the client 
 SSH runs at TCP / IP port 22
 
 Step 1 : $ Services SSH start 
Step 2 : $ SSH username@ipaddress
   
#  File permissions change related in linux📸🐱
   
   #  $chmod 🐱‍👤
   
   Chmod is used to chnage the access permissions of files and directories. It stand for chnage mode  
 Option: 
    '+' stands for add
    '-' stands for remove

   
   
   
  
