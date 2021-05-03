**Linux Commands with Examples**

The Linux command is a utility of the Linux operating system. All basic and advanced tasks can be done by executing commands. The commands are executed on the **Linux terminal**. The terminal is a command-line interface to interact with the system, which is similar to the command prompt in the Windows OS. *Commands in Linux are **case-sensitive**.*

[Linux](https://www.javatpoint.com/linux-tutorial) provides a powerful command-line interface compared to other operating systems such as [Windows](https://www.javatpoint.com/windows) and MacOS. We can do basic work and advanced work through its terminal. We can do some basic tasks such as creating a file, deleting a file, moving a file, and more. In addition, we can also perform advanced tasks such as administrative tasks (including package installation, user management), networking tasks (ssh connection), security tasks, and many more.

Linux terminal is a user-friendly terminal as it provides various support options. To open the Linux terminal, press "**CTRL + ALT + T**" keys together, and execute a command by pressing the '**ENTER**' key.

In this topic, we will discuss the top 50 most frequently used Linux commands with their examples. These commands are very useful for a beginner and professional both. We have divided these commands into following sections so that you can easily identify their usage:

- [Linux Directory Commands](https://www.javatpoint.com/linux-commands#Directory)
- [Linux File Commands](https://www.javatpoint.com/linux-commands#File)
- [Linux File Content Commands](https://www.javatpoint.com/linux-commands#Content)
- [Linux User Commands](https://www.javatpoint.com/linux-commands#User)
- [Linux Filter Commands](https://www.javatpoint.com/linux-commands#Filter)
- [Linux Utility Commands](https://www.javatpoint.com/linux-commands#Utility)
- [Linux Networking Command](https://www.javatpoint.com/linux-commands#Networking)
## **Linux Top 50 Commands**
The following are the top 50 Linux commands:
### **Linux Directory Commands**
**1. pwd Command**

The [pwd](https://www.javatpoint.com/linux-pwd) command is used to display the location of the current working directory.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. pwd  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples1.png "IMG\_256")

**2. mkdir Command**

The [mkdir](https://www.javatpoint.com/linux-mkdir) command is used to create a new directory under any directory.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. mkdir <directory name>  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples2.png "IMG\_257")

**3. rmdir Command**

The [rmdir](https://www.javatpoint.com/linux-rmdir) command is used to delete a directory.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. rmdir <directory name>  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples3.png "IMG\_258")

**4. ls Command**

The [ls](https://www.javatpoint.com/linux-ls) command is used to display a list of content of a directory.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. ls  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples4.png "IMG\_259")

**5. cd Command**

The [cd](https://www.javatpoint.com/linux-cd) command is used to change the current directory.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. cd <directory name>  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples5.png "IMG\_260")
### **Linux File commands**
**6. touch Command**

The [touch](https://www.javatpoint.com/linux-touch) command is used to create empty files. We can create multiple empty files by executing it once.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. touch <file name>  
1. touch <file1>  <file2> ....  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples6.png "IMG\_261")

**7. cat Command**

The [cat](https://www.javatpoint.com/linux-cat) command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. cat [OPTION]... [FILE]..  

To create a file, execute it as follows:[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)

1. cat > <file name>  
1. // Enter file content  

Press "**CTRL+ D**" keys to save the file. To display the content of the file, execute it as follows:[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)

1. cat <file name>  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples7.png "IMG\_262")

**8. rm Command**

The [rm](https://www.javatpoint.com/linux-rm) command is used to remove a file.

**Syntax:**

rm <file name>

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples8.png "IMG\_263")

**9. cp Command**

The [cp](https://www.javatpoint.com/linux-cp) command is used to copy a file or directory.

**Syntax:**

To copy in the same directory:[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)

1. cp <existing file name> <new file name>  

To copy in a different directory:

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples9.png "IMG\_264")

**10. mv Command**

The [mv](https://www.javatpoint.com/linux-mv) command is used to move a file or a directory form one location to another location.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. mv <file name> <directory path>  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples10.png "IMG\_265")

**11. rename Command**

The [rename](https://www.javatpoint.com/linux-rename) command is used to rename files. It is useful for renaming a large group of files.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. rename 's/old-name/new-name/' files  

For example, to convert all the text files into pdf files, execute the below command:[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)

1. rename 's/\.txt$/\.pdf/' \*.txt  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples11.png "IMG\_266")
### **Linux File Content Commands**
**12. head Command**

The [head](https://www.javatpoint.com/linux-head) command is used to display the content of a file. It displays the first 10 lines of a file.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. head <file name>  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples12.png "IMG\_267")


**13. tail Command**

The [tail](https://www.javatpoint.com/linux-tail) command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. tail <file name>  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples13.png "IMG\_268")

**14. tac Command**

The [tac](https://www.javatpoint.com/linux-tac) command is the reverse of cat command, as its name specified. It displays the file content in reverse order (from the last line).

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. tac <file name>  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples14.png "IMG\_269")

**15. more command**

The [more](https://www.javatpoint.com/linux-more) command is quite similar to the cat command, as it is used to display the file content in the same way that the cat command does. The only difference between both commands is that, in case of larger files, the more command displays screenful output at a time.

In more command, the following keys are used to scroll the page:

**ENTER key:** To scroll down page by line.

**Space bar:** To move to the next page.

**b key:** To move to the previous page.

**/ key:** To search the string.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. more <file name>  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples15.png "IMG\_256")

**16. less Command**

The [less](https://www.javatpoint.com/linux-less) command is similar to the more command. It also includes some extra features such as 'adjustment in width and height of the terminal.' Comparatively, the more command cuts the output in the width of the terminal.

**Syntax:**

[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)

1. less <file name>  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples16.png "IMG\_256")
### **Linux User Commands**
**17. su Command**

The [su](https://www.javatpoint.com/linux-su-commands) command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. su <user name>  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples17.png "IMG\_257")

**18. id Command**

The [id](https://www.javatpoint.com/linux-id-command) command is used to display the user ID (UID) and group ID (GID).

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. id  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples18.png "IMG\_258")

**19. useradd Command**

The [useradd](https://www.javatpoint.com/linux-create-user) command is used to add or remove a user on a Linux server.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. useradd  username  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples19.png "IMG\_259")

**20. passwd Command**

The [passwd](https://www.javatpoint.com/linux-user-password) command is used to create and change the password for a user.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. passwd <username>  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples20.png "IMG\_260")

**21. groupadd Command**

The [groupadd](https://www.javatpoint.com/linux-add-user-to-group) command is used to create a user group.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. groupadd <group name>  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples21.png "IMG\_261")
### **Linux Filter Commands**
**22. cat Command**

The [cat](https://www.javatpoint.com/linux-cat-filters) command is also used as a filter. To filter a file, it is used inside pipes.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. cat <fileName> | cat or tac | cat or tac |. . .   

**Output:**

![IMG\_262](https://static.javatpoint.com/linux/images/linux-commands-with-examples22.png "IMG\_262")

**23. cut Command**

The [cut](https://www.javatpoint.com/linux-cut) command is used to select a specific column of a file. The '-d' option is used as a delimiter, and it can be a space (' '), a slash (/), a hyphen (-), or anything else. And, the '-f' option is used to specify a column number.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. cut -d(delimiter) -f(columnNumber) <fileName>  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples23.png "IMG\_263")

**24. grep Command**

The [grep](https://www.javatpoint.com/linux-grep) is the most powerful and used filter in a Linux system. The 'grep' stands for "**global regular expression print**." It is useful for searching the content from a file. Generally, it is used with the pipe.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. command | grep <searchWord>  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples24.png "IMG\_264")

**25. comm Command**

The ['comm'](https://www.javatpoint.com/linux-comm) command is used to compare two files or streams. By default, it displays three columns, first displays non-matching items of the first file, second indicates the non-matching item of the second file, and the third column displays the matching items of both files.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. comm <file1> <file2>  

**Output:**

![IMG\_265](https://static.javatpoint.com/linux/images/linux-commands-with-examples25.png "IMG\_265")

**26. sed command**

The [sed](https://www.javatpoint.com/linux-sed) command is also known as **stream editor**. It is used to edit files using a regular expression. It does not permanently edit files; instead, the edited content remains only on display. It does not affect the actual file.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. command | sed 's/<oldWord>/<newWord>/'  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples26.png "IMG\_266")

**27. tee command**

The [tee](https://www.javatpoint.com/linux-tee) command is quite similar to the cat command. The only difference between both filters is that it puts standard input on standard output and also write them into a file.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. cat <fileName> | tee <newFile> |  cat or tac |.....  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples27.png "IMG\_267")

**28. tr Command**

The [tr](https://www.javatpoint.com/linux-tr) command is used to translate the file content like from lower case to upper case.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. command | tr <'old'> <'new'>  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples28.png "IMG\_268")

**29. uniq Command**

The [uniq](https://www.javatpoint.com/linux-uniq) command is used to form a sorted list in which every word will occur only once.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. command <fileName> | uniq  

**Output:**

![IMG\_269](https://static.javatpoint.com/linux/images/linux-commands-with-examples29.png "IMG\_269")

**30. wc Command**

The [wc](https://www.javatpoint.com/linux-wc) command is used to count the lines, words, and characters in a file.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. wc <file name>  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples30.png "IMG\_270")

**31. od Command**

The [od](https://www.javatpoint.com/linux-od) command is used to display the content of a file in different s, such as hexadecimal, octal, and ASCII characters.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. od -b <fileName>      // Octal format  
1. od -t x1 <fileName>   // Hexa decimal format  
1. od -c <fileName>     // ASCII character format  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples31.png "IMG\_271")

**32. sort Command**

The [sort](https://www.javatpoint.com/linux-sort) command is used to sort files in alphabetical order.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. sort <file name>  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples32.png "IMG\_272")

**33. gzip Command**

The [gzip](https://www.javatpoint.com/linux-gzip) command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. gzip <file1> <file2> <file3>...  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples33.png "IMG\_256")

**34. gunzip Command**

The [gunzip](https://www.javatpoint.com/linux-gzip) command is used to decompress a file. It is a reverse operation of gzip command.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. gunzip <file1> <file2> <file3>. .  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples34.png "IMG\_257")
### **Linux Utility Commands**
**35. find Command**

The [find](https://www.javatpoint.com/linux-find) command is used to find a particular file within a directory. It also supports various options to find a file such as byname, by type, by date, and more.

The following symbols are used after the find command:

(.) : For current directory name

(/) : For root

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. find . -name "\*.pdf"  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples35.png "IMG\_258")

**36. locate Command**

The [locate](https://www.javatpoint.com/linux-locate) command is used to search a file by file name. It is quite similar to find command; the difference is that it is a background process. It searches the file in the database, whereas the find command searches in the file system. It is faster than the find command. To find the file with the locates command, keep your database updated.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. locate <file name>  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples36.png "IMG\_259")

**37. date Command**

The [date](https://www.javatpoint.com/linux-date) command is used to display date, time, time zone, and more.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. date  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples37.png "IMG\_260")

**38. cal Command**

The [cal](https://www.javatpoint.com/linux-cal) command is used to display the current month's calendar with the current date highlighted.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. cal

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples38.png "IMG\_261")

**39. sleep Command**

The [sleep](https://www.javatpoint.com/linux-sleep) command is used to hold the terminal by the specified amount of time. By default, it takes time in seconds.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. sleep <time>  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples39.png "IMG\_262")

**40. time Command**

The [time](https://www.javatpoint.com/linux-time) command is used to display the time to execute a command.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. time  

**Output:**

![IMG\_263](https://static.javatpoint.com/linux/images/linux-commands-with-examples40.png "IMG\_263")

**41. zcat Command**

The zcat command is used to display the compressed files.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. zcat <file name>  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples41.png "IMG\_264")

**42. df Command**

The [df](https://www.javatpoint.com/linux-df) command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. df  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples42.png "IMG\_265")

**43. mount Command**

The [mount](https://www.javatpoint.com/linux-mount) command is used to connect an external device file system to the system's file system.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. mount -t type <device> <directory>  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples43.png "IMG\_266")

**44. exit Command**

Linux [exit](http://javatpoint.com/linux-exit-command) command is used to exit from the current shell. It takes a parameter as a number and exits the shell with a return of status number.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. exit  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples44.png "IMG\_267")

After pressing the ENTER key, it will exit the terminal.

**45. clear Command**

Linux **clear** command is used to clear the terminal screen.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. clear  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples45.png "IMG\_268")

After pressing the ENTER key, it will clear the terminal screen.
### **Linux Networking Commands**
**46. ip Command**

Linux [ip](https://www.javatpoint.com/linux-ip) command is an updated version of the ipconfig command. It is used to assign an IP address, initialize an interface, disable an interface.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. ip a or ip addr  

**Output:**

![IMG\_269](https://static.javatpoint.com/linux/images/linux-commands-with-examples46.png "IMG\_269")

**47. ssh Command**

Linux [ssh](https://www.javatpoint.com/ssh-linux) command is used to create a remote connection through the ssh protocol.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. ssh user\_name@host(IP/Domain\_name)</p>  

**48. mail Command**

The [mail](https://www.javatpoint.com/linux-mail-command) command is used to send emails from the command line.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. mail -s "Subject" <recipient address>  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples48.png "IMG\_270")

**49. ping Command**

The [ping](https://www.javatpoint.com/linux-ping) command is used to check the connectivity between two nodes, that is whether the server is connected. It is a short form of "Packet Internet Groper."

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. ping <destination>  

**Output:**

![](https://static.javatpoint.com/linux/images/linux-commands-with-examples49.png "IMG\_271")

**50. host Command**

The [host](https://www.javatpoint.com/linux-host) command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

**Syntax:[**](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)[](https://www.javatpoint.com/linux-commands)**

1. host <domain name> or <ip address>  

**Output:**

![IMG\_272](https://static.javatpoint.com/linux/images/linux-commands-with-examples50.png "IMG\_272")
