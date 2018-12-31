# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)

`pwd`: show current working directory path
`mkdir`: creating a directory
`rm -rf`: deleting a directory
`touch <file name>`:creating a file using `touch` command
`rm <file name>` : deleting a file
`mv <old file name> <new file name>` : renaming a file
`ls -a`: listing hidden files
`cp <file name> <directory path/>` : copying a file from one directory to another
`cat <file name>` : print the file on standard output
`mkdir -p <path of directory>` : creating the nested directories
---

### Q2.  List Files in Unix   

What do the following commands do:

`ls` - list files in the directory.
`ls -a` - list all the files in the directory including all hidden files.
`ls -l` - list all the files in long format.
`ls -lh` - list all the files in long format and human readable file sizes.
`ls -lah` - list all the files including hidden files in long format and human readable file sizes.
`ls -t`  - sort the files with modified time.
`ls -Glp` - 'G'enables colorised output and 'p'adds '/' for directories while listing the files.
---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

`ls -a` : Display all files.
`ls -d` : Displays only directories.
`ls -R` : Displays subdirectories as well.
`ls -t` : Displays newest files first. (based on timestamp)
`ls -1`  : Displays each entry on a line.
---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > xargs allows command such as 'echo','rm' and 'mkdir' to accept standard input as arguments.
ex: echo dsp1  dsp2| xargs mkdir 

