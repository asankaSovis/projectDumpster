# projectDumpster
## --Overview--
I created this repository to look for folders in the system and other places of the operating systems that contain junk files. My main goal is to create a collection of junk file locations that can be used by people to know which folders need cleaning. Also if it goes successful, also start working on a system cleaning software for windows and later other OS. Anyone is welcome to collaborate. Please comment if you have concerns.

## --About--
I have noticed that there doesn't exist a proper collection of data for which files/folders that are unwanted in the operating system and can be removed. Also I have noticed that there doesn't exist many opensource cleaner apps for Windows. This repository will hopefully one day, resolve both these issues.

## --How to Contribute--
Inside the main repository, there exist a folder 'Cleanup Lists'. This contains the lists of cleaning paths. For example, 'Windows OS' contain sub-lists of locations that belong to the 'Windows Operating System'. Under this folder, there exist files with sub-lists of locations. For example 'Windows System', which contains locations that belong to the System of the OS. Create a new branch and add any paths you have found and create a pull request. Make sure to add a descriptive comment.

## --Structure of the Location Path List--
The structure of the lists is made as:
####  {name for the folder}|{location path for file/folder}|{your username}|{comments}
If the location path contains a changing term, for example in the path 'C:\Users\username\AppData\Local\Temp'; the 'username' changes from computer to computer. Thus replace 'username' with '{username}' for convenience.
an example is:
####  'System temporary folder|C:\Users\{username}\AppData\Local\Temp|asankaSovis|Delete all files'
