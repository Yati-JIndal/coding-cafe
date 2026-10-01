question 1: What did `pwd` print?
pwd known as the present working directory, Tells you where you are standing. For me pwd printed "/Users/Yatijindal", as this is where I am standing right now in the computer. It is a string of navigation locations (Branches of locations). It is altogether a path, i.e. where are you standing inside the computer application. It is kind of a tree like structure that the computer is organised into.


question 2: What did `ls -a` show that plain `ls` did not?
ls -a shows the hidden files in a particular location in the computer whereas the ls just lists the files it can see or read in that location.
ls, known as list. It is the list all the things that are there in your laptop desktop, i.e. list of all the files in a location.
ls -a known as the list of all. It shows the hidden files in a particular location—> [-a] = all


question 3: Pick one line from `ls -l`. What do you think the first column means?
ls -l—> gives us a complete expanded list of all the files. It gives a longer description of all the file names, Permissions, and ownership informations, also the creation and editing information.
One line from the ls -l
"drwx------@   4 yatijindal  staff   128 25 Jul 20:47 Applications"
here the drwx---@ means that this file is a directory (d) whereas the rwx refer to the permissions.
4 refers to the number of hard links to the directory.
yatijindal - refers to the owner this directory belongs to.
staff - group associated with the directory
128 - it refers to the size of the file in bytes
25 Jul 20:47 - refers to the last date and time that this file was modified.
Applications - It is the name of the directory


question 4: Why does that work from where you are standing? Which kind of path is `coding-cafe/week02`? Absolute or Relative?
The creation of the coding cafe file happens from where we are, as we have created the file in the same location itself. 
"coding-cafe/week02" is an relative pathway because, we donot have to give the terimal the basic input of where exactly is this file located, as we are already present and working in that location.


question 5: `mv` did two different jobs above. What were they?
mv was used in 2 places that are
(i) "mv README-BACKUP.MD WEEK01/" 
(ii) "mv README-backup.md old-readme.md"
In the (i), the mv moved the README-BACKUP file from the coding-cafe folder to the week 01 folder in the coding cafe directory.
In the (ii), the mv renamed/ replaced the README-BACKUP file to the old-readme file in the week 01 folder of the coding cafe directory.


question 6: How many folders are on your `PATH`? (They are separated by `:`)
There are 11 folders in my PATH.


question 7: **Write down exactly where your `python3` lives.**
"/Library/Frameworks/Python.framework/Versions/3.14/bin:" this is where exactly the python3 lives.


question 8: Compare your answer to 7 with the person next to you. Are they the same? If not, why might that be?
No, they are not same as everyone has a different computer with a different location of of their python3 pathway, as it might be stored/saved in a different location.


question 9: What exactly did the shell say? Explain the error in your own words, using the word **PATH**.
The shell shows error, as it mentions that no such command is found in the zsh that is name "pyton3". PATH is basically a list of all the folders where the terminal looks, when it is finding a particular file or folder. When we type a copmmand, like "pyton3" here, now this doesnot exist in the PATH therefore, it shows that there is an error in the input.


question 10: `.venv` did not appear with plain `ls`. Why not? (Refer back to section 1.)
.venv does not appear with plain ls, because it is a hidden directory and the plain ls cannot read the hidden directories. Whereas, we can see .venv in ls -a, because it shows all the files including the hidden directories.


question 11: What changed about your prompt?
The main change is that .venv appears at the beginning of the prompt


question 12: Compare this with what you wrote down for question 7. Is it the same path? If not, what does that tell you about what `activate` actually did to your `PATH`?
On comparing it with the path in question 7, I observe that after adding the (.venv), there has been a change in the location of the file, as before the first file was of python3 but after (.venv), it has moved to being the second file. The first file of .venv has been added. ACTIVATE has actually activated the virtual python environment and that is the file that has been added to the PATH.


question 13: What is in the second list that was not in the first?
"/Users/yatijindal/coding-cafe/.venv/bin:" The addition of this file in the second list is what is different. This file was not in the first list because their was no activation of the python virtual environmnet.


question 14:  Where does `python3` point now?
which python3 gives a different output in .venv and without iy. Now deactivating .venv has put my file back to normal. python3 now points pack to the original location it was initially in.


question 15: Find what `ls -h` does. Write it in your own words.
ls -h means list files with human readable data. when using the command ls -h, it is giving the information about all the files existing that are in my current location.


question 16: What is the difference between what Ctrl + C and Ctrl + D did?
Ctrl C (command C, for mac) is used for copying a particular line, word or number whereas Ctrl D (command D, m=for mac) is used for checking how many times has the same word, number or line been repeated or used. It higlights the word, line,number.
