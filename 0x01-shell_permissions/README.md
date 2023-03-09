shell permissions
su betty :a script that switches the current user to the user betty.
You should use exactly 8 characters for your command (+1 character for the new line)
You can assume that the user betty will exist when we will run your script
whoami :a script that prints the effective username of the current user.
chmod --reference=olleh hello :a script that sets the mode of the file hello the same as olleh’s mode.

The file hello will be in the working directory
The file olleh will be in the working directory
julien@ubuntu:/tmp/h$ ls -l
chown vincent:staff * :a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
chown -h vincent:staff _hello :a script that changes the owner and the group owner of _hello to vincent and staff respectively.
The file _hello is in the working directory
The file _hello is a symbolic link
chown --from=guillaume betty hello :a script that changes the owner of the file hello to betty only if it is owned by the user guillaume.
The file hello will be in the working directory
telnet towel.blinkenlights.nl   a script that will play the StarWars IV episode in the terminal.
chmod -R +X . :a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
Regular files should not be changed.
mkdir -m 751 my_dir:a script that creates a directory called my_dir with permissions 751 in the working directory.
chgrp school hello :Write a script that changes the group owner to school for the file hello
The file hello will be in the working directory
groups :a script that prints all the groups the current user is part of.
chown betty hello :a script that changes the owner of the file hello to the user betty
touch hello :a script that creates an empty file called hello.
chmod u+x hello:a script that adds execute permission to the owner of the file hello.
The file hello will be in the working directory
chmod ug+x,o+r hello :a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
The file hello will be in the working directory
chmod ugo+x hello :a script that adds execution permission to the owner, the group owner and the other users, to the file hello
The file hello will be in the working directory
You are not allowed to use commas for this script
chmod 007 hello :Write a script that sets the permission to the file hello as follows:
Owner: no permission at all
Group: no permission at all
Other users: all the permissions
chmod 753 hello : a script that sets the mode of the file hello to this:-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello

