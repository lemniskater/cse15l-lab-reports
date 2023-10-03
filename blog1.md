# My Blog for Lab_1

## Using cd

 **without arguments** 
 
![Image](cdnoargs.png)
 
- cd prints and *seems to do nothing*, the working directory was /home when run with no arguments. It is not an error since I did not specify any directory
  
 **with a path to a directory** 
 
![Image](image.png)
 
- From /home I see now I am in the directory I specified which is lecture1/messages which is *not an error*.

**with a path to a file as an argument**
  
![Image](cdfile.png)
  
- From /home/lecture1/messages it states that the file is not a directory and does nothing, this can be considered an *error* as I used cd on a file which *won't do anything*.

## Using ls

**without arguments**

![Image](lsnoarg.png)

* In /home/lecture1/messages ls prints out all the txt file names present in the messages folder, this is not an error.

**with a path to a directory** 

![Image](lsdir.png)

* In /home I used ls on lecture1 to print out all file names in lecture1

**with a path to a file** 

![Image](lsfile.png)

* In /home I used ls on /lecture1/messages/en-us.txt and it just seems to print out the path to the specified file.

## Using cat

**without arguments**

![Image](catnoargs.png)

* In /home running cat without arguments seemed to make the terminal run infinitely and I had to stop using ctrl + c. This seems to be an error because of the fact that the terminal stopped working as intended.

**with a path to a directory** 

![Image](catdir.png)

* In /home I used cat to specify lecture1 and it printed out lecture1 is a directory.

**with a path to a file** 

![Image](catfile.png)

* In /home I used cat /lecture1/messages/en-us.txt and it printed out the contents of the .txt file. 
