0-hello_world:When you execute the script ./0-hello_world, it will print "Hello, World" followed by a new line to the standard output.
1-confused_smiley:When you execute the script ./1-confused_smiley, it will display "(Ôo)'" on the standard output.
 2-hellofile:When you execute the script ./2-hellofile, it will display the content of the /etc/passwd file on the standard output.
 3-twofiles:When you execute the script ./3-twofiles, it will display the content of both the /etc/passwd and /etc/hosts files on the standard output.
 4-lastlines:When you execute the script ./4-lastlines, it will display the last 10 lines of the /etc/passwd file on the standard output.
 5-firstlines:When you execute the script ./5-firstlines, it will display the first 10 lines of the /etc/passwd file on the standard output.
6-third_line:When you execute the script ./6-third_line, it will display the third line of the file iacta on the standard output. The script uses the head and tail commands to extract the third line from the file.
 7-file:After running the script, you can verify the file creation using ls -l and check its contents using cat -e '*\\'"Best School"\'\\*$\?\*\*\*\*\*:).
8-cwd_state:When you run the script (./8-cwd_state), it will execute the ls -la command and redirect the output to the ls_cwd_content file. After running the script, you can verify the contents of the file using cat ls_cwd_content.
9-duplicate_last_line:When you run the script, it will use the sed command to extract the last line of the file iacta and append it to the end of the file.
10-no_more_js: When you run the script, it will use the find command to locate all regular files (-type f) with a .js extension (-name "*.js") in the current directory and its subfolders, and then delete them using the -delete option.
11-directories:This script counts the number of directories and sub-directories in the current directory, excluding the current and parent directories. It excludes hidden directories and outputs the total count.
12-newest_files:This script displays the 10 newest files in the current directory. The files are listed one per line, sorted from the newest to the oldest.
13-unique:This script takes a list of words as input and prints only the words that appear exactly once
14-findthatword:  This script displays lines containing the pattern "root" from the file /etc/passwd
gep -c "bin" /etc/passwd:This script counts the number of lines that contain the pattern "bin" in the file /etc/passwd
16-whatsnext:This script displays lines containing the pattern "root" and 3 lines after them in the file /etc/passwd
17-hidethisword:This script displays all the lines in the file /etc/passwd that do not contain the pattern "bin"
18-letteronly:This script displays all lines of the file /etc/ssh/sshd_config starting with a letter
19-AZ:This script replaces all occurrences of 'A' with 'Z' and 'c' with 'e'
20-hiago:This script removes all occurrences of 'c' and 'C' from input
21-reverse:This script reverses its input
22-users_and_homes:This script displays all users and their home directories, sorted by users.
