This is a list of scripts that help you do useful stuff in shell.

1. 0-current_working_directory prints the absolute path name of your current working directory

2. 1-listit displays the content list of your current directory.

3. 2-bring_me_home changes your working directory to your home directory.

4. 3-listfiles displays the contents of your current directory in a long format.

5. 4-listmorefiles displays the contents of your current directory, including hidden files, in long format.

6. 5-listfilesdigitonly displays the content of your current directory including hidden files, in long format and with user and group IDs displayed numerically.

7. 6-firstdirectory creates a directory named 'my_first_directory' in the /tmp directory.

8. 7-movethatfile moves a file 'betty' from /tmp to /tmp/my_first_directory.

9. 8-firstdelete deletes the file 'betty' from /tmp/my_first_directory.

10. 9-firstdirdeletion deletes the directory 'my_first_directory' that is in the /tmp directory.

11. 10-back changes the working directory to the previous one.

12. 11-lists list all files (including hidden files) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

13. 12-file_type prints the type of file named 'iamafile' in /tmp.

14. 13-symbolic_link creates a symbolic link to /bin/ls named __ls__. Link is created in current working directory.

15. 14-copy_html copies

16 100-lets_move moves all files beginning with an uppercase letter to the directory `/tmp/u`

17. 101-clean_emacs deletes all the files in the current working directory that end with character `~`.

18. 102-tree creates three directories `welcome/`, `welcome/to/` and `welcome/to/school` as a directory tree in the current directory.

19. 103-commas lists all the files and directories of the current directory, separated by commas ie `,`. The list will go thus :

   * Directory names should end with `/`
   * Hidden files should be listed
   * The listing should be alpha ordered, except for the directories `.` and `..` which should be at the beginning.
   * Only digits and letters are used to sort; Digits comes first

