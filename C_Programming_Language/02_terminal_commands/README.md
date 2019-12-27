# Basic Terminal Command

Hi, in this tutorial I will go over ten basic terminal commands. These are part of my regular work flow.

If you are not interested in learning the terminal commands then skip to the next video where I actually start coding in C.

* ## 1:`ls` - stands for List. Lists computer files.
	* 1: `ls` - Lists computer files of the current directory.
	* 2: `ls -a` - Lists computer files of the current directory including hidden files and folders
	* 3: `ls -l` - Long list format that gives additional information about files and folders. 
	* 4: `ls -la` or `ls -al` - Long list format that gives additional information about files and folders including hidden files and folders. 
	* 5: `ls -G` - Colorizes files, folder, and executables in different colors.
* ## 2: `mkdir` - stands for make directory. Creates a folder or directory.

First command I will show is LS, which stands for List. It lists computer files. Now there is a lot that can be covered just on LS, but I will go over the basics, which in most cases should be enough.
LS -a - will show you all the files and folders, including hidden files. How can you tell which files and folders are hidden? When a file or directory begins with a Period that’s how you will know those files and folders are hidden.
LS -l - l stands for Long listing format and this gives you additional information about the file. I use this command a lot just because I want to see files in a column.
LS -la - This command combines the l and a flag, so it shows you all files and folders including hidden. And because we have l, it will show all the files and folders in the long listing file format.
ls -G - Capital G will will show you files, folders, and executables in different colors. I dont really use this command a lot. I think windows and linux by default show you files and folders in color. But if you are on mac and you want to distinguish between files, folders, and executables, this command should help.
This should wrap up the LS command.

	2. MKDIR
Next command we will look at is mkdir, which stands for make directory. And as the name suggests it makes directories, we will create a few folders.
mkdir empty_folder1
mkdir empty_folder2
mkdir “empty folder 3”
mkdir empty_folder3 empty_folder4 empty_folder5 - This will create all these folders in one go. and we will type ls to see these folders.
This is it for the mkdir command

3. cd
Next command we will look at is cd, which stands for change directory. And this changes directories.

	4. pwd
Next command we will look at is pwd, which shows you the full pathname of the current working directory.

	5. touch
Next command we will look at is touch, which creates a file. You can do few more things with it and change the modification time of a file. But I have mostly only used it to create some empty files.
touch empty_file1
touch “empty file 2”
touch file1 file2 file3 file4
6. mv
Next command we will look at is mv, which stands for move. And this command moves files, but it can also rename files.
First we will create empty files:
touch file1 file2 file3 file4 file5 file6
		Then we will create empty directories:
mkdir folder1 folder2 folder3 folder4 folder5 folder6





	
	7. rm
Next command we will look at is rm, which is used to remove files. I would be careful when using this command because unlike deleting files the regular way which moves the file or folder in the “Trash” or “Recycle bin”, rm command will completely remove the file. There might be ways to recover it, but I am not familiar with those methods. First I will show you how to remove files and folders and then I will share a safe method to remove files.
		First we will create empty files:
touch file1 file2 file3 file4 file5 file6
		Then we will create empty directories:
mkdir folder1 folder2 folder3 folder4 folder5 folder6
		Now we will run the rm command to remove files
rm file1
rm file2 file3
rm file* - This will remove all the files that begin with “file”
Now we will run the rm command to remove folders
rm -rf folder1
rm -rf folder2 folder3
rm -rf folder*
That’s how we remove files and folders. Now as I mentioned earlier, there are ways to remove files safely.
One thing that I have heard friends do is set an alias for the rm command, so the rm command moves the the file or folder to “Trash” or “Recycle bin” instead of completely removing them.
Method that I personally use to safely remove files especially when I am working on a project with a lot of files and folders. I will create a new folder, let’s call it to_be_deleted. And I will do mkdir to_be_deleted to create the folder. Now anytime I want to delete a file, what I will do is, I will move that file over to this directory called to_be_deleted.
When I’m done I will run just once “rm -rf to_be_deleted”. This way we are only running the remove command once, which has been really helpful for me to safely remove files. 

	8. Cat
Next command we will look at is cat, which stands for concatenate. Now it does two things. It can concatenate several files. And it can show the contents of one or as many files as you want.
	First we will create some files.




	9. cp
	
	10. chmod

	11. echo

