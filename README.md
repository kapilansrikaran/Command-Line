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
| cd .. | change to parent directory |
| pwd | display current dir path |
| cp | copying files and directories to another location
| useradd | add new user in the system | 
| usermod | modify user |
| userdel | delete user |
| groupadd | add new group in the system |
