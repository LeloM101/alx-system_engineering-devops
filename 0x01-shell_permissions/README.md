#!/bin/bash
su betty – changed betty to current user

whoami - prints the effective username of the current user

groups - prints all the groups the current user is part of

touch hello – makes new empty file

sudo chown betty hello – changed owner of file hello to betty

chmod u+x hello - script that adds execute permission to the owner of the file hello

chmod ug+x,o+r  hello - script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello

chmod a+x hello – give execution permission to all

chmod 007 hello – others have all permissions

chmod 753 hello – script for given mode

chmod --reference olleh hello – tried to be like another file

chmod 755 */ - script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.

mkdir -m 751 my_dir - script that creates a directory called my_dir with permissions 751 in the working directory

chgrp school hello - script that changes the group owner to school for the file hello

