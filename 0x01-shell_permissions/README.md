Here we have more commands useful for modifying user data and permissions.


1. 0-iam_betty switches the current user to the user betty

2. 1-who_am_i prints the effective username of the current user

3. 2-groups prints out all groups the current user is in

4. 3-new_owner changes the owner of a file

5. 4-empty creates an empty file called hello

6. 5-execute adds execute permission to the owner of the file hello

7. 6-multiple_permissions adds execute permission to the owner and group owner, and read permission to other users, to the file hello

8. 7-everybody adds execution permission to the owner, the group owner and the other users, to the file hello

9. 8-James_Bond sets permission to file hello thus:
  - Owner: no permissions at all
  - Group: no permissions at all
  - Other users: all the permisions

10. 9-John_Doe sets mode of file hello thus:
  - Owner: all permissions
  - Group: Read and Execute
  - Other users: Write and execute

11. 10-mirror_permissions sets the mode of file hello to the same mode as file olleh

12. 11-directories_permissions adds execute permission to all subdirectories of the current directory for the owner, group owner and all other users
