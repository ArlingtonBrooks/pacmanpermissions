# pacmanpermissions
fix file permissions using pacman

This is a simple shell script for anyone who's messed up their file system permissions on Arch Linux.  This uses `pacman` as well as `pacutils` to determine the intended permissions and correct them.  

This is a possible solution to fix permissions on Arch using pacman.  There is no guarantee.  


#KNOWN BUGS
Any files containing the words "permission" or "UID" or "GID" will cause some strange behavior since the file lists are retrieved using a simple 'grep'.  
