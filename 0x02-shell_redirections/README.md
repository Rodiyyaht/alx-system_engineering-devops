Task 0: echo Hello, World; It prints Hello, world by using echo.

Task 1: echo "\"(Ôo)'"; It prints "(Ôo)' using echo.

Task 2: cat /etc/passwd; It displays the content of /etc/passwd

Task 3: cat /etc/passwd /etc/hosts; Displays the content of /etc/passwd and /etc/host.

Task 4: tail /etc/passwd; Displays the last 10 lines of /etc/passwd.

Task 5: head /etc/passwd; Displays the first 10 lines of /etc/passwd.

Task 6: head --lines=3 iacta | tail --lines=1; Display the third line of iacta.

Task 7: echo "Best School"> "\*\\\'\"Best School\"\'\\\*$\?\*\*\*\*\*:)"; creates the file  "\*\\\'\"Best School\"\'\\\*$\?\*\*\*\*\*:)" containing Best School..

Task 8: ls -la > ls_cwd_content; Writes the ls -la into ls_cwd_content.

Task 9: echo -en "" | tail --lines=1 iacta >> iacta; Duplicates, the last line of iacta.

Task 10: find . -name '*.js' -type f -delete; Deletes all files in current directory and subfolder that has js. extension.

Task 11: find -mindepth 1 -type d | wc -l; Counts the directory and subdirectory in the current directory.

Task 12: ls -t | head; Displays the newest 10 files.

Task 13: sort | uniq -u; Making it unique.

Task 14: grep -i root /etc/passwd; Displaying the pattern root in /etc/passwd in the line.

Task 15: grep -i bin /etc/passwd | wc -l; Word count for word with /bin.

Task 16: grep -iA 3 root /etc/passwd.

Task 17: grep -iv bin /etc/passwd; Display all the lines in files that does not contain bin.

Task 18: grep -i "^[a-z]" /etc/ssh/sshd_config; Displaying all lines of the file starting with capital letter.

Task 19: tr Ac Ze; Replace A and c with Z and e.

Task 20: tr -d cC; Removes all lettters c and C from input.

Task 21: rev; Reverse its input.

Task 22: cut -d':' -f1,6 /etc/passwd | sort; Displays all users and are their home directories soreted by users.

Task 23: find . -empty -printf "%f\n";  A command that finds all empty files and directories in the current directory and all sub-directories.

Task 24: find -type f -name "*.gif" -printf "%f\n" | rev | cut -d'.' -f 2- | rev | LC_ALL=C sort -f;  A script that lists all the files with a .gif extension in the current directory and all its sub-directories.

Task 25: cut -c 1 | tr -d '\n' | sort; .

Task 26: tail -n +2 | cut -f1 | sort | uniq -c | sort -nr | head -11 | tr -s ' ' | cut -d' ' -f3.