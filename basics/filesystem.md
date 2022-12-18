# Filesystem

## File Types

### Regular File Types
- images
- scripts
- configuration files
- data files

### Directory
A directory is a file that contains a list of other files and directories.

### Special File
- character files
- block files
- links
  - hard links
  - symbolic links
- socket files
- named pipes

### Use the file command to check the file type
```bash	
file abc-script.sh
```	

### Fist letter identifies the file type
- d: directory
- -: regular file
- c: character file
- l: symbolic link
- s: socket file
- p: named pipe
- b: block file

e.g. from the directory home:
```bash
ls -ld
```
output:	
```bash
drwxr-xr-x 3 root root 4096 May 30  2021 .
```