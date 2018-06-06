# Git-Test-Project
This repository is used to teach students command line git with the following exercises (page references for book <i>Learn Version Control with Git</i> by Tobias Günther:

### Exercise 1-2
1. Create a folder called GitTestProject and navigate to the folder in Terminal.app.
2. Run the "git clone" command on p 28 to copy the repository at to your https://github.com/CS-STech/Git-Practice-Ch1 GitTestProject folder.
3. Navigate into the new folder created.
4.Run "git config --global color.ui auto" so your changes will be displayed in color.
5. Open WebCourses.txt in a text editor and add the following lines at the end:
```
CSCI 1150 - Introduction to Frameworks 
CSCI 1155 - Introduction to Cloud Services 
```
6. Run the "git status" command.
7. Use the "git add" command to stage the changes made to WebCourses.txt.
8. Run the "git status" command to make sure you're prepared to commit.
9. If everything looks correct, commit the changes with an appropriate message.
10. Run the "git log" command.

### Exercise 1-3
1. Navigate to the Git-Test-Project folder in Terminal.app.
2. Create a new file SoftwareCourses.txt in a text editor and add the following lines:
```
SWATC 1000 - Student Success
CSCI 1160 - Computer Science Fundamentals
WKSK 1405 - Work Place Relations
SWDM 1031 - Intro to Design Principles
SWDM 1012 - Introduction to Media Design
CSCI 1100 - Version Control Management
CSCI 1105 - Introduction to Programming
CSCI 1110 - Object Oriented Programming
CSCI 1115 - Algorithms & Data Structures
ITEC 2905 - Capstone Project
```
3. Run the "git status" command.
4. Erase EmptyFile.txt.
5. Run the "git status" command.
6. Use the "git add" command to stage the changes made to SoftwareCourses.txt.
7. Run the "git status" command to make sure you're prepared to commit.
8. If everything looks correct, commit the changes with an appropriate message.
9. Use the "git rm" command to stage the changes made to EmptyFile.txt.
10. Run the "git status" command to make sure you're prepared to commit.
11. If everything looks correct, commit the changes with an appropriate message.
12. Run the "git log" command.
