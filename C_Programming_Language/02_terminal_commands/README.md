# Basic Terminal Command

Hi, in this tutorial I will go over ten basic terminal commands. These are part of my regular work flow.

If you are not interested in learning the terminal commands then skip to the next video where I actually start coding in C.

* ### 1:`ls` - Stands for List. Lists computer files.
	* `ls` - Lists computer files of the current directory.
	* `ls -a` - Lists computer files of the current directory including hidden files and folders
	* `ls -l` - Long list format that gives additional information about files and folders. 
	* `ls -la` or `ls -al` - Long list format that gives additional information about files and folders including hidden files and folders. 
	* `ls -G` - Colorizes files, folder, and executables in different colors.
* ### 2:`mkdir` - Stands for make directory.
	* `mkdir empty_folder1` - Creates a directory called empty_folder1.
	* `mkdir empty_folder2 empty_folder3 empty_folder4` - Creates multiple directories called empty_folder2, empty_folder3 and empty_folder4.
	* `mkdir "empty folder 4"` - Creates a directory called "empty folder 4". Words are seperated by spaces.

* ### 3:`cd` - Stands for change directory.
	* `cd name_of_folder` - Enter the directory called "name_of_folder".
* ### 4:`pwd` - Shows full pathname of the current working directory.
* ### 5:`touch` - Creates a file.
	* `touch empty_file1` - Creates a file called empty_file1.
	* `touch "empty file 2.txt"` - Creates a file called "empty file 2.txt". Words are seperated by spaces.
	* `touch empty_file2 empty_file3 empty_file4` - Creates multiple files.
* ### 6:`mv` - Stands for move. Moves files and folders. And also renames files and folders.
	* `mv old_file_name new_file_name` - Renames file "old_file_name" to "new_file_name".
	* `mv old_file_name "new file name"` - Renames file "old_file_name" to "new file name".
	* `mv file1 folder2` - If a directory called folder2 exists then moves file1 inside directory "folder2".
* ### 7:`rm` - Removes files and folders.
	* `rm file1` - Removes file called file1.
	* `rm -rf folder1` - Removes a directory called folder1.
* ### 8:`cat` - Concatenates multiples files and shows contents of files.
	* `cat file1 file2 file3 > file4` - Concatenates contents of file1, file2, file3 into file4. If file4 does not exist then it will be created. But if file4 already has content that content will completely removed.
	* `cat file1` - Shows content of file1
	* `cat file1 file2 file3 "file 4"` - Shows content of all files.
* ### 9:`cp` - Copies files and directories.
	* `cp source_file destination_file` - Copies the contents of the source_file to destination_file. If destination_file does not already exist then a destination_file will be created. If destination_file already exists then file will be overwritten. Old content or data will be removed and data of the source_file will show.
	* `cp -a source_folder destination_folder` - Copies all the contents of the source_folder to destination_folder.
* ### 10:`chmod` - Changes permissions of files and folders.
	* `chmod 0 file_name folder_name` - No one can access these files and folders.
	* `chmod 777 file_name folder_name` - If files or folders previously had permission denied, then gives everyone access and permission to read, write, and execute files and folders.
	
