# Linux Privilege Escalation - Enumeration Commands

This repository contains a collection of useful Linux commands for performing enumeration tasks, particularly for privilege escalation scenarios. These commands help gather information about the system, processes, users, network, and files. It's essential to exercise caution and ensure proper authorization before executing any actions. 
<center>
<a href="https://twitter.com/th3wantedboy">
      <img src="https://img.shields.io/twitter/follow/th3wantedboy?style=social">
  </a>
      </center>
      <br/>

## Basic System Info:

- **`hostname`**: Displays the system hostname.
- **`uname -a`**: Prints system information.
- **`cat /proc/version`**: Shows the kernel version.
- **`cat /etc/issue`**: Displays distribution information.

## Process Information:

- **`ps`**: Lists running processes.
- **`ps -a`**: Lists all processes.
- **`ps axjf`**: Displays processes in a tree.
- **`ps aux`**: Lists all processes with user information.

## Environment & Permissions:

- **`env`**: Prints environment variables.
- **`sudo -l`**: Shows sudo privileges.
- **`ls`**: Lists files and directories.
- **`ls -la`**: Lists detailed file information.

## User & Group Info:

- **`id`**: Displays user and group IDs.
- **`cat /etc/passwd`**: Shows user account information.
- **`cat /etc/passwd | cut -d ":" -f 1`**: Lists usernames.
- **`cat /etc/passwd | grep home`**: Filters by home directories.
- **`cat /etc/passwd | grep /bin/bash`**: Filters by shell type.

## Network Info:

- **`ifconfig`**: Displays network interfaces.
- **`ip route`**: Shows the routing table.
- **`netstat`**: Lists network statistics.
- **`netstat -l`**: Lists listening sockets.
- **`netstat -a`**: Displays active connections.
- **`netstat -ano`**: Shows connections with PIDs.

## File System Search:

- **`find . -name {file name}`**: Searches for files.
- **`find /home -name {}`**: Searches in a directory.

## Command History:

- **`history`**: Shows command history.

## Additional Commands and Techniques:

- **`lsblk`**: Lists block devices.
- **`df -h`**: Displays disk space usage.
- **`du -sh *`**: Shows disk usage of files and directories.
- **`grep -r {pattern} {directory}`**: Searches for a pattern recursively in a directory.

Feel free to use these commands to gather information effectively. These are basic commands, and there are more advanced techniques available for system enumeration.
Always ensure proper authorization and use caution when performing any actions on a system.
<center>
<a href="https://twitter.com/th3wantedboy">
      <img src="https://img.shields.io/twitter/follow/th3wantedboy?style=social">
  </a>
      </center>
      <br/>
