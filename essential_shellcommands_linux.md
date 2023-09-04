# Essential Shell Commands for Linux


## 1. Navigation

| **Command** | **Description** |
| --- | --- |
| `pwd` | Print working directory: This shows the current directory you are in. |
| `ls` | List files and directories: Lists the files and directories in the current directory. |
| `cd` | Change directory: Changes the current directory. |
| `history` | Displays the history of previously executes commands. |

## 2. File and Directory Management

| **Command** | **Description** |
| --- | --- |
| `mkdir` | Make directoty: Creates a new directory. |
| `rmdir` | Remove directory: Deletes a directory. |
| `cp` | Copy file/directory: Copies files or directories. |
| `mv` | Move file/directory: Moves files or directpries. |
| `rm` | Remove file: Deletes a file. |
| `touch` | Create a file: Creates a new empty file. |
| `find` | Searches for files and directories. |
| `grep` | Searches for a pattern in a file. |
| `head` | Shows the first 10 lines of a file. |
| `tail` | Shows the last few lines of a file. |

## 3. Text Manipulation

| **Command** | **Description** |
| --- | --- |
| `cat` | Concatenate files: Displays the contents of a file. |
| `less` | Display output one screen at a time: Shows the output of a command one screen at a time. |
| `awk` | Manipulate and analyze text files: Manipulates and analyzes text files. |
| `sed` | Stream editor for filtering and transforming text: perform text transformations on an input stream. |
| `vi` or `vim` | a text editor for creating and editing text files. |
| `nano` | a text editor used to create and edit text files. |
| `emacs` | a highly customizable text editor for editing and document preparation tasks. |
| `echo` | Print to the screen: Displays text on the screen.

## 4. Compression and Archiving

| **Command** | **Description** |
| --- | --- |
| `tar` | Archive files: Compresses and archives files. |
| `gzip` | Compress files: Compresses files. (and **gunzip**)
| `zip` | Compress files into a zip archive: Compresses files into a zip archive. (and **unzip**)

## 5. Permissions and Ownership

| **Command** | **Description** |
| --- | --- |
| `sudo` | This command is used to execute a command with elevated privileges. |
| `su` | This command is used to switch to another user account in the current shell session. |
| `unmask` | This command is used to set the default file creation permissions for new files and directories. |
| `chmod` | Change file permissions: Changes the permissions of a file. |
| `chown` | Change file owner: Changes the owner of a file. |

## 6. System Information

| **Command** | **Description** |
| --- | --- |
| `ps` | Show the running processes: Displays the running processes on the system. Also, see `pstree`. |
| `top` | Show the system status: Displays the system status. Also, see `htop`, `btop` and `atop`. |
| `free` | Show the system memory usage: Displays the memory usage of the system. |
| `df` | Show the disk space usage: Displays the disk space usage of the system. |
| `du` | Show the disk usage of a file or directory: Displays the disk usage of a file or directory. |
| `which` | Show the location of a command: locate the executable file associated with a given command. |
| `man` | Show the manual of a command: Shows the manual page for a command. |

## 7. Networking

| **Command** | **Description** |
| --- | --- |
| `ip` | Used to view and manage network interfaces and routing tables. |
| `ss` | Used to view network sockets and their related information. |
| `dig` | Used to query DNS (Doman Name System) servers for DNS-related information. |
| `ping` | Test network connectivity: Tests the network connectivity to a host. |
| `ssh` | Connect to a remote system: Connects to a remote system over SSH. |
| `scp` | Copy files to/from a remote system: Copies files to/from a remote system. |
| `rsync` | remote sync: A file synchronization tool for Unix/Linux systems. |
| `curl` | Transfer data from a server: Transfers data from a server usind carious protocols. |
| `wget` | Download files from the web: Downloads files from the web. |

## 8. Text Processing

| **Command** | **Description** |
| --- | --- |
| `sort` | Sort lines of text: Sorty the lines of a text in a file. |
| `uniq` | Sgow unique lines o text: Displays only the unique lines of a text in a file. |
| `diff` | Show differences between files: Compares two files and shows the differences. |
| `cut` | Cut out specific sections of a file: Extracts specific columns from a file. |
| `paste` | Merge lines of files: Merges lines from multiple files. |

## 9. Scheduling

| **Command** | **Description** |
| --- | --- |
| `crontag` | Schedule commands to run at specific times: Schedules commands to run automatically. |
| `at` | Schedules a one-time task to be executed at a specific time in the future. |
| `anacron` | Executes commands periodically (ex, daily, weekly and monthly), especially for systems not running 24/7.
| `batch` | Schedules commands to be executed when system load levels permit. |

