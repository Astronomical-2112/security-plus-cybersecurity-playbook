- sudo 
sudo is a program for evoking super user privlages, you can also log in as root if you have that set up, but sudo is faster and only requires that your account has super user privlages.
If you run a command and it bounces back the fact that you lack permissions to continue, you can append sudo and it will work.  However you should only do this if you absolutely trust the program.
Otherwise you should not

- ls
ls (meaning List) is a command that lists everything in a directory, by default it lists everything in an active directory, 
but you can type in a path for any directory.

- ipfw
ipfw (stands for IP firewall) is a command that lets you configure your firewall from the terminal.
I had a spare computer I ran a minecraft server on and I had to use ipfw because 
I was remoting in from my desktop, and because of that I didn't have a spare monitor for.
ipfw set lets you enable or disable any rules, and ipfw -cq lets you add new rules.

- dpkg
dpkg is a program that helps you install package files, mostly used for installing local packages as apt lets you install them from repos.

- apt
apt is a linux package manager, one of the first ones that let you download software from a repo.  It uses dpkg to install them once downloaded.
You can use it by typing in apt install xyz (xyz filling in for whatever you want) if you are not logged in as root you need to evoke sudo privlages
by typing sudo apt install xyz.  Update by typing sudo apt update and then after sudo apt upgrade.  

- nano
nano is a terminal text editor.  It excells at letting you create shell scripts very quickly without needing to open a text editor. 

- man
man prints off the manual for whatever command you want to use. Typing in "man cd" will print the user manual for the command cd.

- info
info is a more detailed version of man.  Some distros don't ship info, as it is less popular, 
as while it has more information, man still gives you plenty of information and it being shorter makes it an easier read.

- echo
echo prints text in the command line.  if you typed in "echo Hello World" you would see Hello World printed, 
you can use different forms of flow control to control when stuff is printed.  This is very useful for shell scripts.

- cd
cd is a command that changes the directory that bash is currently accessing.  You can type in a relative path, or an absolute path.

- cp 
cp is a command that lets you copy a file from one location to another.  You first type in cp,
and then you type in the file you want to be copied, and then you type in the path of the location you want it to be copied to.

- tar
tar is a command that allows the user to compress an entire directory into one file.  tar -c lets you create a new archive. 
The first argument is for what you want to archive, and the second is used to point to where you want the archive to be output to.
tar -cfz can be uses to compress the archive as well using gzip.

- gzip
gzip is a file compressor that only compresses one file.  Unlike other compression programs it can't compress multiple files. 
Compressed files replace the uncompressed one.  

- mkdir
mkdir makes a directory in the current directory, or at the path specified.

- bzip2 
bzip2 is an alternate compression tool that works similarly to tar. 

- rm
rm is a program for deleting a file, rm -rf can remove a directory.

- grep
grep is used to search for text inside files.

- cat
cat prints out text output from a file. 

- lspci
displays information about pci devices.

- lscpu 
displays information about your cpu

- jobs
displays active jobs going on

- groupadd
adds a defined user to a group

- ifconfig
ifconfig, or interface config is used for configuring network interfaces

- w
displays information on every user logged into a computer and what they are doing

- getent
short for get enteries, it works similarly to cat but also can get user info from accounts that may not be stored locally

- head
lets you preview the contents of a logfile by showing you the start of it

