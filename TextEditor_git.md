# Git

### Cheatsheet

This is a reference list of the most commonly used Git commands. 

 - <ins>**Commands related to a remote repository:**
 ```
 1. git clone git@github.com:USER-NAME/REPOSITORY-NAME.git

2. git push or git push origin main (Both accomplish the same goal in this context)
```
- <ins>**Commands related to the workflow:**
```
- git add .

- git commit -m <font color="red">"A message describing what you have done to make this snapshot different"</font>
```

- <ins>Commands related to checking status or log history
```
- git status
- git log
```

The basic Git syntax is program | action | destination.

For example,

- <ins>**git add .</ins>** is read as <ins>**git | add | .**</ins>  , where the period represents everything in the current directory;

- <ins>git commit -m "message"</ins> is read as git | commit -m | "message"; an

- <ins>git status</ins> is read as git | status | (no destination).

>Link directo a la clase de Odin que habla de este tema [Here](https://www.theodinproject.com/lessons/foundations-git-basics).

--- 

### <mark>Four streps for save any modificaded file<mark>

   
   1. Save your progress in de Vs Code with the command **ctrl + s** 
   
   2. Type <ins>**git status**</ins> in the terminal and look the files are modificaded
   3. Type <ins>**git add**</ins> < name of the file>
   
   4. git commit -m "Edit README.md and hello_world.txt"

   
   and if you want upload your files in the github, after thos three steps, type in the terminal:

   - <ins>**git push**</ins>

   Remenber always stay in the <mark>correct folder!<mark>
 
 ---
   ## <ins>how create a new folder and files</mark>

   1. Create a folder with command <ins>mkdir</ins>
2. Create a file with command <ins>touch</ins>
