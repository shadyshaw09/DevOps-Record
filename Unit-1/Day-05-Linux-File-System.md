Day 05 - Linux File System
Date: 14-02-2026

Objective: To understand the Linux file system structure and file management concepts.
Introduction: The Linux file system follows a hierarchical structure that starts from the root directory (/). Everything in Linux is treated as a file, including hardware devices.
The structure is organized in directories and subdirectories.
Important Directories in Linux:



(Root)  

The top-level directory of the Linux system.
home  

Contains user personal directories.



root  
Home directory of the root user.



etc  
Stores system configuration files.



var  
Contains log files and variable data.



bin  
Contains essential system binaries (commands).



usr  
Contains user-installed programs and utilities.



tmp  
Temporary files storage.
File Types in Linux:



1. Regular files

2. Directories

3. Symbolic links

4. Device files

File Management Commands Practiced:

ls -l  

Shows detailed file information

cp  

Copies files

mv  

Moves or renames files

rm -r  

Removes directories

df -h  

Displays disk space usage

du -h  

Displays directory size

Importance in DevOps:



Understanding file systems is important because:

- Log files are stored in specific directories

- Configuration files are located in /etc

- Docker and other services use Linux directory structure

Conclusion:

Today I learned about Linux file system hierarchy, important directories, and file management commands used in real-world DevOps environments.

