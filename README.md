# HW_1 for GEOG693  

## Basic Shell Exercise   

_Problem:_ You are getting ready to input all your field data and metadata from your 25 study sites.  You want to be sure that all your directories and files are organized in exactly the same way but pointing and clicking is time consuming and error prone.  You can solve this by writing a script to make the directories and files for you automagically.

_Objective:_ Create a series of Bash/Unix commands that successfully:  
1) Creates the hierarchy of directories and files represented by the diagram below.
2) Then deletes them. You decided to quit your RA and be a river guide.  

![directory structure](./images/Slide1.jpeg)


Adhere to the following principles:
1)	Make the paths __relative__ so that I can reproduce the structure on my machine simply by running your code. Ideally, the directories would be set up below my current working directory. 
2)	Code should be saved as two blocks of bash commands in an `.md` file  
  * the first block should make the directories  
  * the second block should delete the directories  

3)	Code should include comments that explain each line in your script. These can be written as text around the block in the `.md` or preceded by a `#`.

5)	The fewer lines of code, the better the answer. Edit your answer until only what is required is present. 9 lines of code or less is possible.

#### Example:

##### JanesCommands.md
Brief set of commands to view the working directory, see what's in it, make a new directory
```
pwd #get the current working directory
ls #list the files/folders in the current working directory
mkdir data #makes a new directory called data
```
Now delete that new directory:
```
rmdir data #deletes directory called data
```

Hints: Here are some commands and flags you might want to use:

`pwd`  
`mkdir -p`  
`touch`  
`cp -r`  
`rm -r -I` #remember to use carefully!

#### To Submit
Your `.md` file

#### How to Submit
1) Fork the repository  
2) Clone the repository to your computer  
3) Make a new branch  
4) Modify the files  
5) Commit changes  
6) Create a pull request on the original repository to turn in the assignment.  
