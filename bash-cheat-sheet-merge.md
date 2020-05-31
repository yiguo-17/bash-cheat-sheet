# bash-cheat-sheet

## directory

### navigaton
1. ~：home =/users/User_name
2. pwd : Show current path
3. cd : move to target directory by cd [path]. cd can only followed by one directory
4. cd- : move to previous path
5. *absolute_path* and *relative_path*: *absolute_path* describe file or directory's path from home,*relative_path*in a directory describe file or directory's path from a peer of the current directory
### operation
1. ls: list files in current path
2. mkdir: creat one or more new directory by mkdir [path(optinal)]/[directory1] [path(optinal)]/[directory2].
3. mkdir -p: make parent directory as necessary e.g. mkdir -p term-1/week-2 
4. rm -r: remove directory and all the files in it by rm -r [path]

## ls options
1. -a : showing all (including hidden ones)
2. -s : showing file size
3. -1 : showing one derectory or file per line
4. -R : recursive list,  showing all the directories and files in current path (including sub directories and files in there)
5. -h : human readable
6. ls and followed by multiple options in on command line e.g. ls ~/Documents -1 -a -s -h: list all files in documents directory with their file size in one column  
7. .. : check all contents of previous folder(parent folder)
8. ls command can work on multiple path e.g. ls ~/Documents ~/Downloads : list the directories on both downloads and documents folders.


## file
1. touch: creat one or more new files by touch  [path(optinal)]/[file_name1.file_type] [path(optinal)]/[file_name2.file_type].
2. mv: move one or more files by mv[file_name1.file_type] [path]
3. mv: rename a file by mv [file_name1.file_type] [file_name2.file_type]
4. rm: remove one or more files by rm [file_name1.file_type] [file_name2.file_type] 
5. cp: make a copy file to current path must rename the copy file by cp [file_name1.file_type] [file_name2.file_type]; make a copy to a different path by cp [file_name1.file_type] [path]

## support 
1. man: show the reference manual for a operation.
2. code: opens current path in Visual Studio Code.   [code (path, file)
3. cmd + D ====    makes new pane in terminal vertically split
4. cmd + D + Shift ===== makes a new pane in terminal horizontally split