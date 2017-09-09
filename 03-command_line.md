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

> > 1. **pwd**  - print working directory <p>
> > 2. **cd <directory>** - create directory <p>
> > 3. **rm -r <directory>** - delete <directory> <p>
> > 4. **touch <file>** - create an empty file, such as txt <p>
> > 5. **rm <file>** - delete a file <p>
> > 6. **mv <file-old> <file-new>** - rename a file <p> 
> > 7. **ls -la** - list hidden files <p>
> > 8. **cp <file> <directory>** - copy a file from one directory to another <p>
> > 9. **ls** - list documents in the directory folder <p>
> >10. **cat <file>** - output the contents of the file <p>

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

> > **ls** List directory contents <P>
> > **ls -a** lists all files including hidden files <P>
> > **ls -l** (Lower case L) Displays the mode, number of links, owner, group, size (in bytes), and time of last modification for each file. <P>
>> **ls -lh** List Files with Human Readable Format with option –lh <P>
>> **ls -lah** <P>
> > ** t** sort the list of files by modification time. <P>
>> **ls -glp**<P>

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

>> ls [options] [names] <P>
>> -a	Displays all files. <P>
>> -b	Displays nonprinting characters in octal. <P>
>> -c	Displays files by file timestamp. <P>
>> -C	Displays files in a columnar format (default) <P>
>> -d	Displays only directories. <P>

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

>> **One application is to include into one line** <P>
>> **such as: $ seq 5 | xargs echo "hello"** <P>
>> ref as **https://www.youtube.com/watch?v=8kAB_VgokMY**

 
  
**TM: Read through on Sep 9th**
