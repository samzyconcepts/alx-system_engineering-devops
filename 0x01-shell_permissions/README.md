This task is to write out the command line for shell permission

0-iam_betty -switch current user to the user betty

1-who_am_1 -script that prints the username for the current user

2-groups -it prints all the group the current user is part of

3-new_owner -changes the owner of the file to another user

4-empty -creates an empty file called hello

5-execute -this script adds execute permission to owner of a file hello

6-multiple_permissions -adds execute permission to the owner and the group owner, and read permission to other users

7-everybody -adds execution permission to the owner, the group owner and the other user

8-James_Bond -sets the permission to the file hello to as follows:
		Owner: no permission at all
		Group: no permission at all
		Other userd: all the permissions

9-John_Doe -scripts that set the mode of the file hello

10-mirror_permissions -set mode of the file hello the same as olleh's mode

11-directories_permissions -script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all the other users. Regular files should not be changed.

12-directory_permissions -scripts that creates a directory called my_dir with permissions 751 in the working directory

13-change_group -script that changes the group owner to school for the file hello

100-change_owner_and_group -script that change owner to vincent and the group owner to staff for all the files and directories in the working directory

101-symbolic_link_permissions -script that changes the owner and the group owner of _hello to vincent and staff respectively.

102-if_only -script that change the owner of the file hello to betty only if it is owned by the user guillaume.

103-Star_Wars -script that will play the StarWars IV episode in the terminal
