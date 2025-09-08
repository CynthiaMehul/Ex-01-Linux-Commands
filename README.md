# Ex-01-Linux-Commands
## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.

## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

Syntax: ls

<img width="650" height="178" alt="image" src="https://github.com/user-attachments/assets/b5514cf2-ec50-4e3d-ac6d-32a60af91ae0" />

### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="315" height="122" alt="image" src="https://github.com/user-attachments/assets/dba81e50-54ff-47bc-b727-4669314cd2b0" />

### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

<img width="417" height="128" alt="image" src="https://github.com/user-attachments/assets/5ff293b4-a15e-4a8d-bdb7-7c6b518dcb00" />

### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

<img width="607" height="157" alt="image" src="https://github.com/user-attachments/assets/0832dafa-4231-4bdb-8bc4-b609150aa650" />

### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

<img width="302" height="85" alt="image" src="https://github.com/user-attachments/assets/49c7162b-2413-4230-b682-75fa56c887a3" />

### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="291" height="182" alt="image" src="https://github.com/user-attachments/assets/597288cf-3be4-4d16-862d-661dc04489a2" />

### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

<img width="281" height="151" alt="image" src="https://github.com/user-attachments/assets/d1ff3081-7a23-44eb-adcb-ea9bf618b21a" />

### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="1352" height="517" alt="image" src="https://github.com/user-attachments/assets/b2e52dad-a39b-47ac-b47e-18306df4f3c7" />

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

<img width="468" height="327" alt="image" src="https://github.com/user-attachments/assets/bc9c1ec7-3cd7-46e0-9f28-0f93489b773f" />

## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="282" height="147" alt="image" src="https://github.com/user-attachments/assets/a318633d-099e-4386-90c7-057a9f88b394" />

### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

<img width="222" height="510" alt="image" src="https://github.com/user-attachments/assets/2af99470-d0a1-4e28-949d-e8d3ecfe59a6" />

### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

<img width="200" height="507" alt="image" src="https://github.com/user-attachments/assets/bf2e21bc-6389-4648-9eaa-1516cefb01ac" />

### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="820" height="90" alt="image" src="https://github.com/user-attachments/assets/fa60179d-8ec7-496f-89d6-489a16cd884c" />

### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

<img width="318" height="237" alt="image" src="https://github.com/user-attachments/assets/63293a41-bd54-4858-b573-57fae5e95fed" />

### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

<img width="327" height="297" alt="image" src="https://github.com/user-attachments/assets/065bb343-ea5c-4607-b883-ed3f82e7466e" />

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

<img width="215" height="42" alt="image" src="https://github.com/user-attachments/assets/56895a30-44e0-4692-966b-a1ae4f627900" />

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c

<img width="606" height="317" alt="image" src="https://github.com/user-attachments/assets/9a4fdd3e-1f56-4c71-aaed-6b41429c44d4" />

### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

<img width="580" height="125" alt="image" src="https://github.com/user-attachments/assets/da2c3438-c26f-4443-99e5-3403d785ea09" />

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

<img width="566" height="633" alt="image" src="https://github.com/user-attachments/assets/02aa3e66-3a3e-4473-b647-184bc36594b9" />

### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

<img width="642" height="356" alt="image" src="https://github.com/user-attachments/assets/9adb8ad2-726a-46c0-88c5-eb8e93e8c7f9" />

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder

<img width="610" height="218" alt="image" src="https://github.com/user-attachments/assets/dcdd7cde-a4e4-4872-aa39-a3761c0d836d" />
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

<img width="461" height="173" alt="image" src="https://github.com/user-attachments/assets/76cc0316-edb4-4177-a472-4a67359af202" />

### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

<img width="701" height="127" alt="image" src="https://github.com/user-attachments/assets/cc788a65-4da4-4bf1-a5c6-3b0875a3dcfe" />

### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

<img width="206" height="301" alt="image" src="https://github.com/user-attachments/assets/d64b9ec4-52a9-43ab-9b9c-8274370a059f" />

### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

<img width="183" height="156" alt="image" src="https://github.com/user-attachments/assets/000a9488-b079-4749-9774-2ec1bd1bf18c" />

### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>
 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

<img width="712" height="218" alt="image" src="https://github.com/user-attachments/assets/9310c775-6c23-4e1a-a514-19931962cbd1" />

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

<img width="677" height="161" alt="image" src="https://github.com/user-attachments/assets/46204ead-2c12-42c1-8870-d416771633bc" />

### Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
