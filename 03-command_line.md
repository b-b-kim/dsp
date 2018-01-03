# Learn command line

Please follow and complete the free online [Command Line Crash Course
tutorial](https://web.archive.org/web/20160708171659/http://cli.learncodethehardway.org/book/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. Each "chapter" focuses on a command. Type the commands you see in the _Do This_ section, and read the _You Learned This_ section. Move on to the next chapter. You should be able to go through these in a couple of hours.

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

$ pwd * show current working directory
$ mkdir <name_of_new_directory> * create a director
$ rm -r <directory> * delete a directory 
$ touch <directory * create a new file using touch command
$ rm <file> * delete a file
$ mv <oldfilename> <newfilename> * rename a file
$ ls - la * list hidden files
$ cp <file> <directory>  * copying a file from one directory to another
$ ping <host> * ping host and display status
$ head <file> * output first ten lines of file 
                   


---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls` 
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

`ls`   shows files inside current directory
`ls -a`  show hidden files
`ls -l`  shows all information about the file/directory
`ls -lh`  displays file size in human readable form
`ls -lah`  displays long listing in human readable format summarizing file sizes
`ls -t`  opens last edited file in current directory
`ls -Glp`  ?? 

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

ls -r	Displays files in reverse order.
ls -m	Displays the names as a comma-separated list.
ls -ltr will shows latest modification file or directory date as last.
ls -lS displays file size in order, will display big in size first.
ls -lv shows version

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

xargs reads data from standard input (stdin) and executes the command (supplied to it as argument)
  one or more times based on the input read.
  
$ xargs
Hello World  <control +D>
Hello World
$

The above code printed "Hello World" because no echo is the default command for xargs therefore, it simply printed whatever 
input was passed into it.

 

