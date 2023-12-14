# These are the few Linux Commands which we will use below :-

* mkdir
* touch
* rmdir 
* cp
* mv
* rm
* rm -r 
* mkdir {a...z}

##

**1. Make a Directory**
```
mkdir directory_name
```
#### This command is used to create a new directory (folder) in the file system.


![image](https://github.com/raahulahlawat/Linux-Commands/assets/151362887/22e08a92-8b7c-4570-8d18-0be532e50cff)


##

**2. To Open the specific Directory**
``` 
cd directory_name
 ```
 ### This command helps us to open the directory/folder.

 ##


 **4. Remove a Directory**
 ```
 rmdir directory_name
 ```
 ### This command can remove an empty directory.

![image](https://github.com/raahulahlawat/Linux-Commands/assets/151362887/b6a699e1-b2b8-409f-bfb5-0fe3de5ed4b2)


* We have to use the cd command to come out of the particular directory/folder before we delete it because it cannot be deleted if it is already open. 

```
cd directory_name
```

### To remove the directory/folder by using the rmdir the directory/folder must be empty and If there is any file in the directory/folder it will be removed by the following commandd :-

 ```
 rm -r  dirrectory_name
 ```
 
![image](https://github.com/raahulahlawat/Linux-Commands/assets/151362887/32941043-21a6-4ed3-807a-fa88500286df)


##

**3. Create an Empty File**
```
touch filename
```
### The touch command is used to create an empty file. If the file already exists, it updates the timestamp.

![image](https://github.com/raahulahlawat/Linux-Commands/assets/151362887/a71a231e-24e4-4e0f-aa3a-33494adab20f)

* In the above picture, we can see a command 'ls,' which is used to see existing files in a directory.

##

**5. Remove Multiple Files with a Single Command**

```
rm file1 file2 file3
```

### The rm command is used to remove (delete) files. You can provide multiple file names separated by spaces to remove them in a single command.

![image](https://github.com/raahulahlawat/Linux-Commands/assets/151362887/3f8d1651-810b-4f9d-ac81-647403f3cf30)

* If there are files of the same format, they can be deleted by :-
```
rm {a..z}.format
```

## 

**6. Create Multiple Folders (a-z) with a Single Command**
```
mkdir {a..z}
```
```
mkdir dir_name1 dir_name1 dir_name1 ...
```
### This command uses brace expansion to create directories from "a" to "z." Each letter represents a separate directory. The {a..z} syntax generates the range of letters. 

![image](https://github.com/raahulahlawat/Linux-Commands/assets/151362887/4e82a61f-5d59-42cb-ae02-da6e1853a602)

##

**7. Make a Copy of a File**

### This command copies a file from the source to the destination. You can use a dot (.) as the destination to copy the file to the current working directory.

![image](https://github.com/raahulahlawat/Linux-Commands/assets/151362887/1d98f675-a01c-414a-923d-f3ab37fc631d)

* In this command, we have to use another command 'pwd' to know the path of the folder in which we want to copy the file.
```
pwd
```

##

**8. Move or Rename a File**

### The mv command is versatile; it can be used to move a file to a different location or rename a file. If the source and destination are in the same directory, it renames the file.

*To Move :-*
```
mv file_name destination
```
![image](https://github.com/raahulahlawat/Linux-Commands/assets/151362887/60552229-5bbb-4dba-b08c-4955771b80d4)

*To reame :-*

```
mv old_name new_name
```
![image](https://github.com/raahulahlawat/Linux-Commands/assets/151362887/e910a77f-8906-4bfb-813e-1e7a2a7ab536)

##

**9. Remove Content from the Folder without Removing Folder**

### This command removes all files and subdirectories within the specified folder, leaving the folder itself intact. Be cautious when using the -r (recursive) option.
```
rm -r folder/*
```

![image](https://github.com/raahulahlawat/Linux-Commands/assets/151362887/93764640-e530-4b56-92f9-b9b3d84fb959)

##
##

*Document By Rahul Ahlawat*
