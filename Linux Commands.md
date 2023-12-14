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


![Local Image](Screenshot%20from%202023-12-14%2011-35-40.jpg)

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


 ![Local Image](Screenshot%20from%202023-12-14%2011-50-54.jpg)

* We have to use the cd command to come out of the particular directory/folder before we delete it because it cannot be deleted if it is already open. 

```
cd directory_name
```

### To remove the directory/folder by using the rmdir the directory/folder must be empty and If there is any file in the directory/folder it will be removed by the following commandd :-

 ```
 rm -r  dirrectory_name
 ```
 
![Local Image](Screenshot%20from%202023-12-14%2012-07-06.jpg)

##

**3. Create an Empty File**
```
touch filename
```
### The touch command is used to create an empty file. If the file already exists, it updates the timestamp.

![Alt text](<Screenshot from 2023-12-14 12-38-06.png>)

* In the above picture, we can see a command 'ls,' which is used to see existing files in a directory.

##

**5. Remove Multiple Files with a Single Command**

```
rm file1 file2 file3
```

### The rm command is used to remove (delete) files. You can provide multiple file names separated by spaces to remove them in a single command.

![Alt text](<Screenshot from 2023-12-14 13-05-26.png>)

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

![Alt text](<Screenshot from 2023-12-14 14-15-25.png>)

##

**7. Make a Copy of a File**

### This command copies a file from the source to the destination. You can use a dot (.) as the destination to copy the file to the current working directory.

![Alt text](<Screenshot from 2023-12-14 14-23-11.png>)

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
![Alt text](<Screenshot from 2023-12-14 14-33-34.png>)

*To reame :-*

```
mv old_name new_name
```
![Alt text](<Screenshot from 2023-12-14 14-35-18.png>)

##

**9. Remove Content from the Folder without Removing Folder**

### This command removes all files and subdirectories within the specified folder, leaving the folder itself intact. Be cautious when using the -r (recursive) option.
```
rm -r folder/*
```

![Alt text](<Screenshot from 2023-12-14 14-43-53.png>)

##

*Document By Rahul Ahlawat*