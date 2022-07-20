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
         
         
   option – the search result output.
   section number – the section in which to look for the man page.
   command name – the name of the command which man page you want to see.
   
   Example: 
   
   Look for man Pages :
   
The -f option displays all man pages that match the specified command name and states the sections in which the given command is present.

     man -f sleep
       
Display man Pages From Specific Sections:
   
To display the page from a specific section of a manual, use the syntax
 
     man 3 sleep  
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
 #  Important Commands & Operations📸🐱


   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   
   #  $ 🐱‍👤
   
   
   
   #  $ 🐱‍👤
   
   
   
   #  $ 🐱‍👤
   
   
   
   #  $ 🐱‍👤
   
   
   
   
   #  $ 🐱‍👤
   
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
#  Text Logs Related commands in Linux📸🐱


   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   
   #  $ 🐱‍👤

# Gettings System Info in Linux📸🐱


   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
 
 
#  Users and Groups in Linux📸🐱


   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
   
   
   #  $ 🐱‍👤
