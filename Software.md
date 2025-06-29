# Software
## Types Of Software
* System Software: System Software manages the computers Hardware and provides a software for running other software.
    - Operating Systems: Linux, Windows, WSL (Windows Subsystem for Linux)
    - Terminal: Users can interact with the operating system using commands in terninal
* Application Software
 
  
### Operating System
// Write information about Operating System here
- File management
- Memory management
- Storage
- Kernel

## Linux concepts
- Working directory (pwd): The directory terminal is operating on.

## Linux commands
- `clear`: Clears the terminal screen
- `cd`: Go to /root
- `cd ..`: Go back one level
- `cd <name_of_directory?`: Use `cd <name_of_directory>` command to go to a directory (or folder). Example `cd mustafa`.
- `ls -al`: List files in a directory (or folder)
- `pwd`: Print working directory. This command shows the path of current directory.
- `mkdir <name_of_directory>`: Creates a new directory (also called folder).
- `cat <name_of_file>`: Used to see content of a file `<name_of_file>`

## **Example for `cd`, `pwd` and `ls -al`**
```
root@Dragonator:~# pwd
/root
root@Dragonator:~# ls -al
total 52
drwx------  8 root root 4096 Jun 29 05:45 .
drwxr-xr-x 37 root root 4096 Jun 29 03:48 ..
-rw-------  1 root root    6 Jun 22 02:47 .bash_history
-rw-r--r--  1 root root 3106 Apr 22  2024 .bashrc
drwx------  3 root root 4096 Jun 29 05:38 .cache
drwxr-xr-x  3 root root 4096 Jun 29 05:45 .dotnet
-rw-r--r--  1 root root  159 Jun 29 04:34 .gitconfig
-rw-------  1 root root   20 Jun 29 05:32 .lesshst
drwxr-xr-x  3 root root 4096 Jun 29 04:28 .local
-rw-r--r--  1 root root    0 Jun 29 03:48 .motd_shown
-rw-r--r--  1 root root  161 Apr 22  2024 .profile
drwx------  2 root root 4096 Jan  6 23:14 .ssh
drwxr-xr-x  5 root root 4096 Jun 29 05:38 .vscode-server
drwxr-xr-x  3 root root 4096 Jun 29 04:10 mustafa
root@Dragonator:~# cd mustafa/
root@Dragonator:~/mustafa# pwd
/root/mustafa
root@Dragonator:~/mustafa# ls -al
total 12
drwxr-xr-x 3 root root 4096 Jun 29 04:10  .
drwx------ 8 root root 4096 Jun 29 05:45  ..
drwxr-xr-x 3 root root 4096 Jun 29 05:10 'Computer Science'
root@Dragonator:~/mustafa# cd Computer\ Science/
root@Dragonator:~/mustafa/Computer Science# ls -al
total 28
drwxr-xr-x 3 root root 4096 Jun 29 05:10 .
drwxr-xr-x 3 root root 4096 Jun 29 04:10 ..
drwxr-xr-x 8 root root 4096 Jun 29 05:32 .git
-rw-r--r-- 1 root root  610 Jun 29 05:42 GitHub.md
-rw-r--r-- 1 root root  230 Jun 29 05:10 Hardware.md
-rw-r--r-- 1 root root   59 Jun 29 05:10 README.md
-rw-r--r-- 1 root root 1000 Jun 29 06:08 Software.md
root@Dragonator:~/mustafa/Computer Science# pwd
/root/mustafa/Computer Science
```