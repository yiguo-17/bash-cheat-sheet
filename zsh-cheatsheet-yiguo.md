# zsh cheatsheet

## directory

### navigaton
- ~：home =/users/User_name
- pwd:Show current path
- cd:move to target directory by cd [path]. cd can only followed by one directory
- cd-: move to previous path
- *absolute_path* and *relative_path*: *absolute_path* describe file or directory's path from home,*relative_path*in a directory describe file or directory's path from a peer of the current directory
### operation
- ls: list files in current path
- mkdir: creat one or more new directory by mkdir [path(optinal)]/[directory1] [path(optinal)]/[directory2].
- rm -r: remove directory and all the files in it by rm -r [path]

## ls options
- -a: showing all (including hidden ones)
- -R: recursive list,  showing all the directories and files in current path (including sub directories and files in there)
- -s: showing file size 
- -1: one derectory or file or line

## file
- touch: creat one or more new files by touch  [path(optinal)]/[file_name1.file_type] [path(optinal)]/[file_name2.file_type].
- mv: move one or more files by mv[file_name1.file_type] [path]
- rm: remove one or more files by rm [file_name1.file_type] [file_name2.file_type] 

## support 
- man: show the reference manual for a operation.