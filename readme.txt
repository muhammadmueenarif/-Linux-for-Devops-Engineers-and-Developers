Linux is Operating system. It is open source. Free to use. 
There are many linux distributions like kali linux ubunto fedora etc., 
ubunto user friendly while kali is for hackers. 

pwd and default is / directory. this is the highest level of directory. Any directory any or subdirectory,
any file is in the slash directory.

It has directories like boot folder for booting system. 
etc directory for system configuration files. 
dev for all kind of devices like keyboard, mouse microphone etc., 
Home direcotry where user files are stored. Home can have one or more users. 
Then we have media and mnt for mouse and plugable devices like mouse. 
proc direcotry for processes. 
root direcotry is for administrator user. The administrator on any Linux system is called root. You can do 
things like install new software, uninstall software, modify the configuration files of the directory and so on.

var is a very common directory for storing log files.
user directory.
every user has their own home directory and they have many folders in there, for example the documents, desktop 
directory and so on.

touch command to create file. 
rm or rm -rf command to delete the direcotry. 
mkdir to create new folder or direcotry. 

nano to edit and create files directly. 
vim is also editor available but difficult to use and it is old so if you have not used before then don't use 
and use nano. 
echo command will just show same as in the output. 
to use echo in the file, it will overwrite all the file. so to use echo and to add the text at the new line
we will use echo >> myfile.txt and it will add at the end of line. 
but if use single > then it will override the file. 



Package Managers
every Linux system has their own package management system. You can think of it like an app store but then 
command line based. it can also be used with a graphical interface.
There's the Debian Ubuntu Club which has the APT system, Fedora Club. fedora is based company called Red hat.
they use the DNF system.

there's Arch Linux which uses the Pacman system.
every Linux system has their own package management has their own kind of command line app store.

You would open a terminal. simply type uname -a. You'll see the system.
for ubunto we weill need sudo apt. if it was fedora we would need the DNF command. And for arch Pacman it 
really depends on which Linux system you're using.
There are hundreds of those commands and Linux based systems.

But in this course I'll just mention the most popular Linux based systems because those are like the
most supported.
They have their own security team, you'll find the most documentation on that and so on.

So it's a very good choice to go with one of the mainstream Linux distributions rather than something
some Linux based system someone made in their basement that's basically used by 1 or 2 people, because
those might not have their own security team, the software might be outdated and so on.

how do we use apt?
We can use the command apt with command search. So apt search and then any kind of software you're looking for.
For example, maybe we want to do something with audio. So we would type apt search audio and that searches the
Online store for any application that might be related with audio.

apt search web for web browsers. 
apt install softwarename to install. 
apt remove or apt get remove to uninstall or delete the software. 

Linux powers 80% of the web servers. anything you use on the web, you're basically using Linux all the time 
that you might not be aware of it when you're using the web.
the programs that allow for web servers are Apache and Nginx.

Those are the main popular ones.
I recommend using nginx if you're totally new because it's much easier to set up then Apache. Apache is older 
engines can be a bit.
Easier to set up now.

As for scripting languages, there are many scripting languages available and many programming languages.
Basically, every scripting language is available on Linux as it powers so much of the web.

there are different database systems. So whatever base system is running, it's probably available on Linux.
Except if you use some specific Microsoft database, but anything else will be available on Linux whether you 
use MariaDB, PostgreSQL or others SQL based databases.

So if you want to do web development, Linux is a good platform.

version control system. 
github and gitlab to store the code and collaborate with other projects. 
git init to initialiaze local repository. git add to add the changes and git commit to commit the changes. 
git status to check the status and git log to see the history of our commits and git push to push the changes 
live on github.