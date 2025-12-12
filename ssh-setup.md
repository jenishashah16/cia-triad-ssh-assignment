OverTheWire Bandit



* **Level 0** 

	- Connect to bandit.labs.overthewire.org using port 2220 (the port used for OverTheWire Bandit)

&nbsp;	- Username - bandit0

&nbsp;	- Password: bandit0

&nbsp;	- code used: ssh bandit0@bandit.labs.overthewire.org -p 2220



* **Level 1**

	- Use command ls to view the content of home directory

&nbsp;	- A file readme contains the following password and it can be accessed using "cat readme"

&nbsp;	- ls - list directory contents

&nbsp;	- cat - concatenate files and print on the standard output

&nbsp;	- cd - change directory

&nbsp;	- file - determine file type

&nbsp;	- du - estimate file size usage

&nbsp;	- find - search for files in a directory heirarchy

&nbsp;	- Password: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If



* **Level 2**
* 
**&nbsp;**	- Accessing a - filename is different as 'cat -' cannot be used because '-' is used to take input from the keyboard

&nbsp;	- Instead use 'cat ./-' to read password from file '-'

&nbsp;	- Password: 263JGJPfgU6LtdEvgfWU1XP5yac29mFx



* **Level 3**
* 
**&nbsp;**	- Accessing a file '--spaces in this filename--' , starts with a hyphen and has spaces in between.

&nbsp;	- Use quotes while writing commands for such files like "--spaces in this filename--" OR escape spaces, --spaces\\ in\\ this\\ filename--

&nbsp;	- Using spaces can lead to technical complications, especially when working with command-line interfaces, scripting, or web protocols. 

&nbsp;	- Password: MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx



* **Level 4**

	- Accessing a hidden file from the 'inhere' directory

&nbsp;	- Use command 'cd inhere' to change directory

&nbsp;	- Use command 'ls -a' to reveal all files

&nbsp;	- Use 'cat ...Hiding-From-You' to get password

&nbsp;	- Password: 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ



* **Level 5**

	- Accessing a human readble file from the 'inhere' directory

&nbsp;	- Use command 'cd inhere' to change directory

&nbsp;	- Use command 'file ./-file\*' , this will give the file type for each of the files

&nbsp;	- The '-file07' file will have ASCII Text which is only human readable

&nbsp;	- Use command 'cat ./-file07' 

&nbsp;	- Password: 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw



