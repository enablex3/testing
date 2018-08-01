# DIRCRYPT INSTRUCTIONS README
# COPYRIGHT {NO COPYRIGHT JUST MESSING WITH GITHUB AND SCRIPTING}
# Elijah Reyes <ereyes@citadel.edu>

# PACKAGE SUMMARY:
#         This package contains a custom user-made command that "encrypts" the name of a desired
#         directory and recursively copies all the content over to the new one.

SECTION A
=================================================================

A.1 INSTRUCTIONS(As root):

1. Copy "dircrypt" file to /usr/bin
2. Make "dircrypt" exectuble - "chmod +x /usr/bin/dircrypt"
3. Run "dircrypt </full/path/to/dir" from anywhere 

A.2 EXAMPLE(As anyone):

Type:
    1. cd /home/user_a
    2. ls
       {directory_a}
    3. dircrypt /home/user_a/directory_a <ENTER>
    4. cd /home/user_a
    5. ls
    
Result:    
    directory_a 
    retadyi_cro

