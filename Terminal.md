# Practice in the Terminal
### learning terminal with Python can help you become more productive and efficient in your work, and give you the skills and knowledge to tackle a wide range of programming and data-related challenges.
## The Command Line 
The command line works by accepting text commands from the user and then executing those commands as instructions for the computer to perform a specific action. These actions can range from simple file management tasks like creating and deleting files, to more complex system administration tasks like configuring network settings and managing user accounts.

## Basic Navigation 
Linux provides various commands to navigate its directory system:

1. pwd: This command displays the current working directory, which is the directory you are currently in.

2. ls: This command lists the contents of the current directory. It displays only the names of files and directories by default.

3. cd: This command changes the current directory.
4. mkdir: This command creates a new directory. 
5. rmdir: This command removes an empty directory. 

## Files
The Linux file system is case sensitive, which implies that files and directories with distinct cases in their names are deemed distinct. For instance, "file.txt" and "File.txt" are two separate files in Linux.
Moreover, Linux file system is arranged in a hierarchical tree structure, with the root directory situated at the top, and all other directories branching out from it.

## Manual Pages 
You can use the `man` <command> command to access the manual page for a specific command in Linux. For instance, typing `man ls` will display the manual page for the `ls` command.

In addition to that, you can utilize the `man -k <search term>` command to perform a keyword search for all manual pages that contain the provided search term. For instance, running `man -k network` will display a list of all manual pages that contain the keyword "network".

Finally, when you search for a term within a manual page using the `/<term>` command, you can cycle through each instance of the term within the page by using the `n` command. For example, after searching for "sort" using the `/sort` command, you can press the `n` key to move to the next occurrence of the term within the page.

## File Manipulation 
1. Create a new file or directory, use the "touch" or "mkdir" command, respectively.
2. Remove a file, use the "rm" command followed by the name of the file.
3. Remove a directory and its contents, use the "rm" command with the "-r" option.
4. Rename a file or directory, use the "mv" command followed by the current and new names.
5. Copy a file, use the "cp" command followed by the name of the file and the destination.
6. Move a file or directory, use the "mv" command followed by the current location and the new location.

## Important Notes 
    Everything is a file under Linux, even directories.

    Linux is an extensionless system , files can have any extension they like or none at all.

