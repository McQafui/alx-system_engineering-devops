1. echo 'Hello, World' 
prints “Hello, World”, followed by a new line to the standard output.

2. echo '"(Ôo)'\'
script displays a confused smiley "(Ôo)'

3. cat /etc/passwd
displays the content of etc/passwd

4. cat /etc/passwd /etc/hosts
displays the contents of passwd and hosts

5. tail -n 10 /etc/passwd
displays the last 10 lines of /etc/passwd

6. head -n 10 /etc/passwd
displays the first 10 lines of /etc/passwd

7. tail -n 3 iacta | tail -n 1
displays the third line of iacta

8. echo "Best School" > \\\*\\\\"'\"Best School\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\)
creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line

9. ls -la > ls_cwd_content
writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.

10. echo $(tail -n 1 iacta) >> iacta
duplicates the last line of iacta file

11. find . -type f -name "*.js" -delete
deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

12. find -mindepth 1 -type d | wc -l
counts the number of directories and sub-directories in the current directory
