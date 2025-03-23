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
nano is a terminal text editor.  It excells at letting you create shell scripts very quickly without needing to open a text editor