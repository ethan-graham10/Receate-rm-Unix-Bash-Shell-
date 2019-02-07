# Receate-rm-Unix-Bash-Shell-
This script mimics the functionality of the remove 'rm' command in Unix, with added restore capabilities 

Remove 

How-to-use:

    It will work identical to the rm command to remove a file 
    Run the script by inputing: 
    
      bash remove filename
  
Restore

How-to-use:

    Know the inode of the file you want you to restore 
    If you dont, 'ls' the contents of ../deleted  
    Run the script by inputing: 
    
      bash restore filename_inode
    
    Note that for restore, filename is just the basename for the file you want to restore. The file will still be restored to the correct     path regardless. 

