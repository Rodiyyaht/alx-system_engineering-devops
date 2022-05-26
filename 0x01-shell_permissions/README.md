Task 0: su betty; Script that changes your user ID to betty.
Task 1: id -un; It print the effective user ID of current user.
Task 2: id -Gn; It prints all the groups the current user is part of.
Task 3: chown betty hello; Changes the owner of the file hello to the user betty.
Task 4: touch hello; Creating an empty file called hello.
Task 5: chmod u+x hello; Owner is given permission to execute the file hello.
Task 6: chmod ug+x,o+r hello; Owner and group can execute, other users can read.
Task 7: chmod ugo+x or a+x hello; Everyone can execute.
Task 8: chmod 007 hello; Only others can rwx,no permission for owner and group at all.
Task 9: chmod 753 hello; Owner can do all, group can read and execute and others can write and execute.
Task 10: chmod --reference=olleh hello; Referencing olleh to hello, it sets the mode of olleh the same as hello.
Task 11: chmod -R +X .; It adds execute permission to all subdirectories for a.
Task 12: mkdir -m 751 my_dir; Creating a directory called my_dir. 
