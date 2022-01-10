# Command-Line

> Command Line Interface (CLI)\
> Terminal\
> Bash\
> Shell\
> "These terms are not "100%" the same", but because we're just getting started - If you hear these words just know that they are referring to more or less the same thing.

## Learn these basic commands:
```
Open Window: 
$ open .   ->  Mac 
> start .  ->  Windows

Stands for list:
& ls   ->  Mac
> dir  ->  Windows

Change Directory [Same in all platforms]:
$ cd/    ->  Going inside of directory of Inside 
$ cd ..  ->  Going backward of directory 
$ cd     ->  Going root 

Creates a new file:
$ touch index.html   -> Mac/Linux
> echo > demo.txt    -> Windows

Makes a new directory/folder [Same in all platforms]:
$ mkdir project_1

Clearing Command Line:
$ clear   -> Mac/Linux
> cls     -> Windows

Hidden Files:
$ ls -a [-a means all]

```

## Permission denied error? (Mac / Linux)
###### If you get a permissions error somewhere along the line, you might be able to use "sudo", which is your super user account (aka. it's like the admin of your computer that has all the privileges.) Be careful not to overuse this command.
```
$ sudo pwd
```

What is Unix
What is Kurnal 


| Unix Command | Description |
| --- | --- |
| man {command} | Type **man rm** to read the manual for the **rm** command |
| whatis {command} | Give short description of command |
| ls | List file and directories |
| ls -a | List all file and directories "ls -l" lists file in "long format" or "Tabular Format" |
| ls -laF | Show type of each file. " / " = directory, " * " = executable. |
| ls -s | size of the file or directory |
| ls -laR | Recursive listing, with all subdirs |
| mkdir {dirname} | Make a directory |
| cd {directory} | change to named directory |
| cd | change to home directory |
| cd ~ | change to home directory |
| cd .. | change to previous directory |
| pwd | display current dir path |
| cp | copying files and directories to another location |
| cp {file1} {file2} | copy file1 and call it file2 |
|	cp -r {dir1} {dir2} | copy directory and all subdirs |
| mv {oldfile} {newfile2} | move or rename file1 to file2 |
| rm file | remove a file |
| rmdir {directory} | Only works if {dirname} is empty |
| rm -r {directory} | Remove all files and subdirs |
| touch | create a new file |
| cat file | display a content of the file |
| cat > file | create new file or/ remove the privious data and entering new data |
| cat >> file | with out delete privious data and add datas it's call append | 
| cat {newfile} >> {oldfile} | Append newfile to end of oldfile |
| cat < file | show the file data|
| diff {file1} {file2} | Compare two file and show the differences |
| grep '{pattern}' {file} | Find regular expression in file |
| spell {file} | Display misspelled words |
| wc {file} | Count words in file |
| wc -l {file} | Count the number of lines in a file |
| more file | display a file a page at a time |
| who | list user currencly logged in |
| whoami | ony list the user name |
| top | Real time processor and memory usage |
| date | show date and time |
| df | Check system disk capacity |
| du | Check your disk usage and show bytes in each directory |
| du -h | Check your disk usage in a human readable format |
| printenv | Show all environmental variables |
| uptime | Find out system load |
| useradd | add new user in the system | 
| usermod | modify user |
| userdel | delete user |
| groupadd | add new group in the system |


```
- file
d directory,                                            * executable
    ^   symbolic links (?)  file size (bytes)   file name   / directory
    ^           ^               ^                  ^        ^
    drwxr-xr-x 11 valerie    16296  Mar  7 23:25 public_html/
    -rw-r--r--  1 valerie      256  Mar  8 23:42 index.html
                                            ^
     ^^^        user permission  (rwx)      date and time last modified
        ^^^     group permission (rwx)
           ^^^  world permission (rwx)

```

