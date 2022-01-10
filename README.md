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

| Command | Description |
| --- | --- |
| ls | List file and directories |
| ls -a | List all file and directories "ls -l" lists file in "long format" or "Tabular Format" |
| ls -s | size of the file or directory |
| mkdir | Make a directory |
| cd directory | change to named directory |
| cd | change to home directory |
| cd ~ | change to home directory |
| cd .. | change to previous directory |
| pwd | display current dir path |
| cp | copying files and directories to another location |
| cp file1 file2 | copy file1 and call it file2 |
| mv file1 file2 | move or rename file1 to file2 |
| rm file | remove a file |
| rmdir directory | remove directory |
| rm -r directory | remove directory which contain have a file or/ Non empty directory|
| touch | create a new file |
| cat file | display a content of the file |
| cat > file | remove the privious data and entering new data |
| cat >> file | with out deleted previoud data and add datas it's call append | 
| cat < file | input |
| more file | display a file a page at a time |
| who | list user currencly logged in |
| whoami | ony list the user name |
| useradd | add new user in the system | 
| usermod | modify user |
| userdel | delete user |
| groupadd | add new group in the system |

