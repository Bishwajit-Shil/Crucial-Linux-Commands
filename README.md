# Linux Command lines for user

### File Management:
1. **ls**: List directory contents
   ```
   $ ls
   ```

2. **cp**: Copy files and directories
   ```
   $ cp file1.txt file2.txt
   ```

3. **mv**: Move or rename files and directories
   ```
   $ mv file1.txt new_location/
   ```

4. **rm**: Remove files or directories
   ```
   $ rm file.txt
   ```

5. **mkdir**: Create directories
   ```
   $ mkdir directory_name
   ```

6. **rmdir**: Remove directories
   ```
   $ rmdir directory_name
   ```

7. **touch**: Create empty files or update file timestamps
   ```
   $ touch file.txt
   ```

8. **chmod**: Change file permissions
   ```
   $ chmod 755 file.txt
   ```

9. **chown**: Change file ownership
   ```
   $ chown user:group file.txt
   ```

10. **ln**: Create hard or symbolic links
    ```
    $ ln -s /path/to/original /path/to/link
    ```

### File Viewing and Editing:
11. **cat**: Concatenate and display file content
    ```
    $ cat file.txt
    ```

12. **less**: View file content with pagination
    ```
    $ less file.txt
    ```

13. **head**: Output the first part of files
    ```
    $ head file.txt
    ```

14. **tail**: Output the last part of files
    ```
    $ tail file.txt
    ```

15. **nano**: A simple text editor for editing files
    ```
    $ nano file.txt
    ```

16. **vi or vim**: A powerful text editor for editing files
    ```
    $ vi file.txt
    ```

17. **grep**: Search for patterns in files
    ```
    $ grep "pattern" file.txt
    ```

18. **sed**: Stream editor for filtering and transforming text
    ```
    $ sed 's/old/new/' file.txt
    ```

### System Information:
19. **uname**: Print system information
    ```
    $ uname -a
    ```

20. **hostname**: Print or set system name
    ```
    $ hostname
    ```

21. **df**: Report file system disk space usage
    ```
    $ df -h
    ```

22. **du**: Estimate file space usage
    ```
    $ du -sh directory_name
    ```

23. **top**: Display and update sorted information about processes
    ```
    $ top
    ```

24. **free**: Display amount of free and used memory in the system
    ```
    $ free -h
    ```

25. **ps**: Report a snapshot of the current processes
    ```
    $ ps aux
    ```

### Process Management:
26. **ps**: Display information about processes
    ```
    $ ps aux
    ```

27. **kill**: Terminate processes
    ```
    $ kill PID
    ```

28. **pkill**: Send signals to processes based on name
    ```
    $ pkill process_name
    ```

29. **killall**: Kill processes by name
    ```
    $ killall process_name
    ```

30. **jobs**: List active jobs
    ```
    $ jobs
    ```

31. **fg**: Bring job to foreground
    ```
    $ fg %1
    ```

32. **bg**: Send job to background
    ```
    $ bg %1
    ```

33. **nice**: Run a command with modified scheduling priority
    ```
    $ nice -n 10 command
    ```

### Package Management:
34. **apt-get**: Package handling utility for Debian-based systems
    ```
    $ apt-get install package_name
    ```

35. **yum**: Package manager for RPM-based systems
    ```
    $ yum install package_name
    ```

36. **dnf**: Next-generation package manager for RPM-based systems
    ```
    $ dnf install package_name
    ```

37. **pacman**: Package manager for Arch Linux and its derivatives
    ```
    $ pacman -S package_name
    ```

38. **dpkg**: Package manager for Debian-based systems
    ```
    $ dpkg -i package.deb
    ```

39. **rpm**: RPM Package Manager
    ```
    $ rpm -i package.rpm
    ```

40. **snap**: Package manager for snaps (universal Linux packages)
    ```
    $ snap install package_name
    ```

### Networking:
41. **ifconfig**: Configure network interfaces
    ```
    $ ifconfig
    ```

42. **ip**: Show or manipulate routing, devices, policy routing, and tunnels
    ```
    $ ip addr show
    ```

43. **ping**: Send ICMP ECHO_REQUEST to network hosts
    ```
    $ ping example.com
    ```

44. **traceroute**: Print the route packets take to network host
    ```
    $ traceroute example.com
    ```

45. **netstat**: Print network connections, routing tables, interface statistics, masquerade connections, and multicast memberships
    ```
    $ netstat -tuln
    ```

46. **nslookup**: Query Internet name servers interactively
    ```
    $ nslookup example.com
    ```

47. **dig**: DNS lookup utility
    ```
    $ dig example.com
    ```

48. **wget**: Retrieve files from the web
    ```
    $ wget http://example.com/file.txt
    ```

49. **curl**: Transfer data from or to a server
    ```
    $ curl -O http://example.com/file.txt
    ```

### User and Group Management:
50. **useradd**: Create a new user or update default new user information
    ```
    $ sudo useradd -m username
    ```

51. **userdel**: Delete a user account and related files
    ```
    $ sudo userdel username
    ```

52. **passwd**: Change user password
    ```
    $ passwd username
    ```

53. **groupadd**: Create a new group
    ```
    $ sudo groupadd groupname
    ```

54. **groupdel**: Delete a group
    ```
    $ sudo groupdel groupname
    ```

55. **usermod**: Modify a user account
    ```
    $ sudo usermod -aG groupname username
    ```

56. **chgrp**: Change group ownership
    ```
    $ sudo chgrp groupname file.txt
    ```

57. **groups**: Print group memberships for a user
    ```
    $ groups username
    ```

58. **id**: Print real and effective user and group IDs
    ```
    $ id username
    ```

### System Administration:
59. **sudo**: Execute a command as another user, typically the superuser
    ```
    $ sudo command
    ```

60. **su**: Substitute user identity
    ```
    $ su username
    ```

61. **shutdown**: Shutdown or restart the system
    ```
    $ sudo shutdown -h now
    ```

62. **re

boot**: Reboot the system
    ```
    $ sudo reboot
    ```

63. **systemctl**: Control the systemd system and service manager
    ```
    $ sudo systemctl restart service_name
    ```

64. **journalctl**: Query the systemd journal
    ```
    $ journalctl -u service_name
    ```

65. **cron**: Daemon to execute scheduled commands
    ```
    $ crontab -e
    ```

66. **crontab**: Schedule a command to run at a later time
    ```
    $ crontab -l
    ```

67. **service**: Run a System V init script
    ```
    $ sudo service apache2 start
    ```

68. **ufw**: Uncomplicated Firewall
    ```
    $ sudo ufw enable
    ```

### File Compression and Archiving:
69. **tar**: Manipulate archive files
    ```
    $ tar -cvf archive.tar files
    ```

70. **gzip**: Compress or expand files
    ```
    $ gzip file.txt
    ```

71. **bzip2**: Compress or expand files
    ```
    $ bzip2 file.txt
    ```

72. **zip**: Package and compress files
    ```
    $ zip archive.zip files
    ```

73. **unzip**: Unpackage and extract files from a zip archive
    ```
    $ unzip archive.zip
    ```

74. **7z**: Compress or extract 7z files
    ```
    $ 7z a archive.7z files
    ```

### File Transfer:
75. **scp**: Secure copy files between hosts on a network
    ```
    $ scp file.txt user@remote_host:/remote/directory
    ```

76. **rsync**: Remote file synchronization tool
    ```
    $ rsync -avz source_directory/ destination_directory/
    ```

77. **sftp**: Secure file transfer program
    ```
    $ sftp user@remote_host
    ```

### System Monitoring and Performance:
78. **htop**: Interactive process viewer
    ```
    $ htop
    ```

79. **iostat**: Report CPU statistics and input/output statistics for devices and partitions
    ```
    $ iostat
    ```

80. **sar**: Collect, report, or save system activity information
    ```
    $ sar
    ```

81. **vmstat**: Report virtual memory statistics
    ```
    $ vmstat
    ```

82. **nmon**: Performance monitoring tool
    ```
    $ nmon
    ```

### File System Navigation:
83. **cd**: Change the current directory
    ```
    $ cd directory_name
    ```

84. **pwd**: Print the current working directory
    ```
    $ pwd
    ```

85. **find**: Search for files in a directory hierarchy
    ```
    $ find /path/to/search -name "file.txt"
    ```

86. **locate**: Find files by name
    ```
    $ locate file.txt
    ```

87. **which**: Locate a command
    ```
    $ which command
    ```

88. **whereis**: Locate the binary, source, and manual page files for a command
    ```
    $ whereis command
    ```

89. **tree**: List contents of directories in a tree-like format
    ```
    $ tree
    ```

90. **du**: Estimate file space usage
    ```
    $ du -sh directory_name
    ```

### System Utilities:
91. **date**: Print or set the system date and time
    ```
    $ date
    ```

92. **cal**: Display a calendar
    ```
    $ cal
    ```

93. **uptime**: Display how long the system has been running
    ```
    $ uptime
    ```

94. **echo**: Display a line of text
    ```
    $ echo "Hello, World!"
    ```

95. **history**: Display or manipulate the history list
    ```
    $ history
    ```

96. **clear**: Clear the terminal screen
    ```
    $ clear
    ```

97. **sleep**: Delay for a specified amount of time
    ```
    $ sleep 5
    ```

98. **watch**: Execute a program periodically, showing output fullscreen
    ```
    $ watch -n 1 command
    ```

99. **yes**: Output a string repeatedly until killed
    ```
    $ yes "yes"
    ```

100. **man**: Display the manual page for a command
     ```
     $ man command
     ```


