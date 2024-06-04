
# Most Used Linux Commands for DevOps Engineers

As a DevOps engineer, you'll use a variety of commands across different tools and platforms. Here are some of the most commonly used Linux commands:



## 1. File and Directory Operations:

- ls: List directory contents.
- cd <directory>: Change directory.
- pwd: Print working directory.
- cp <source> <destination>: Copy files or directories.
- mv <source> <destination>: Move or rename files or directories.
- rm <file>: Remove files or directories.
- mkdir <directory>: Create a new directory.
- touch <file>: Create a new empty file.
- find <path> -name <filename>: Search for files and directories.
- cat <file>: Concatenate and display file content.
- less <file>: View file content one screen at a time.
- head <file>: Display the first lines of a file.
- tail <file>: Display the last lines of a file.
- chmod <permissions> <file>: Change file permissions.
- chown <owner>:<group> <file>: Change file owner and group.

## 2. Process Management:

- ps: Report a snapshot of current processes.
- top: Display and update sorted information about processes.
- htop: Interactive process viewer (requires installation).
- kill <pid>: Terminate a process by PID.
- killall <process_name>: Terminate all processes with the given name.
- systemctl <command> <service>: Control the systemd system and service manager (start, stop, restart services).
- service <service> <command>: Manage services (start, stop, restart).ps: Report a snapshot of current processes.
- top: Display and update sorted information about processes.
- htop: Interactive process viewer (requires installation).
- kill <pid>: Terminate a process by PID.
- killall <process_name>: Terminate all processes with the given name.
- systemctl <command> <service>: Control the systemd system and service manager (start, stop, restart services).
- service <service> <command>: Manage services (start, stop, restart).
## 3. Networking :

- ifconfig: Configure a network interface (deprecated in favor of ip command).
- ip a: Show addresses of network interfaces.
- ping <host>: Send ICMP ECHO_REQUEST to network hosts.
- netstat: Print network connections, routing tables, interface statistics (deprecated in favor of ss command).
- ss: Display socket statistics.
- curl <url>: Transfer data from or to a server.
- wget <url>: Retrieve files from the web.## 4. Disk Management :

- df -h: Report file system disk space usage.
- du -sh <directory>: Estimate file space usage.
- mount: Mount a file system.
- umount: Unmount a file system.
- fdisk -l: List disk partitions.
## 5. text Processing :

- grep <pattern> <file>: Search for patterns in files.
- awk '{print $1}' <file>: Pattern scanning and processing language.
- sed 's/old/new/g' <file>: Stream editor for filtering and transforming text.
- cut -d '<delimiter>' -f <fields> <file>: Remove sections from each line of files.
## 6. Compression and Archiving :

- tar -cvf <archive.tar> <files>: Create a tarball.
- tar -xvf <archive.tar>: Extract a tarball.
- gzip <file>: Compress files.
- gunzip <file.gz>: Decompress files.
## 7. User and Permission Management :

- adduser <username>: Add a new user.
- deluser <username>: Delete a user.
- usermod -aG <group> <user>: Add a user to a group.
- passwd <username>: Change user password.
## Favorite Commands Asked by Interviewers

**1.Basic Commands:** 
- ls -l: List files in long format.
- grep -r <pattern> <directory>: Recursively search for a pattern in a directory.
- tail -f <file>: Continuously monitor a file for changes.

**2.Networking Commands:** 
- ping: Basic command to check connectivity.
- traceroute <host>: Print the route packets take to the network host.
- curl -I <url>: Fetch the HTTP headers of a URL.

**3.Process and System Management:** 
- ps aux | grep <process>: Search for a process by name.
- df -h: Check disk space usage.
- top: Monitor system performance and process activity.
- systemctl status <service>: Check the status of a service.

**4.File Operations and Text Processing:** 
- find / -type f -name <filename>: Find files by name.
- sed 's/foo/bar/g' <file>: Replace all instances of 'foo' with 'bar' in a file.
- awk '{print $2}' <file>: Print the second column of a file.

**4.User Management:** 
- sudo adduser <username>: Add a new user with superuser privileges.
- usermod -aG sudo <username>: Add a user to the sudo group.
- passwd <username>: Change the password for a user.

                 THANK YOU!!!
