# Git-Practice-Ch1
This repository is used to teach students command line git with the following exercises (page references for book <i>Learn Version Control with Git</i> by Tobias Günther [ISBN: 9781520786506; <a href="https://www.git-tower.com/learn/">Website</a>]):

### Exercise 1-2
1. Navigate onto the Desktop.
2. Run the "git clone" command to copy the repository at <a href="https://github.com/CS-STech/Git-Practice-Ch1">https://github.com/CS-STech/Git-Practice-Ch1</a>. Refer to p 28 for an example.
3. Navigate into the new folder created.
4. Run "git config --global color.ui auto" so your changes will be displayed in color.
5. Open WebCourses.txt in a text editor (such as Sublime) and add the following lines at the end:
```
CSCI 1150 - Introduction to Frameworks 
CSCI 1155 - Introduction to Cloud Services 
```
6. Run the "git status" command. WebCourses.txt should be displayed in red.
7. Use the "git add" command to stage the changes made to WebCourses.txt.
8. Run the "git status" command to make sure you're prepared to commit. WebCourses.txt should be displayed in green.
9. If everything looks correct, commit the changes with an appropriate message.
10. Run the "git log" command.
11. After successful completion of the previous steps, take a screenshot of the terminal showing the commands for steps 1-4 and 6-10.

### Exercise 1-3
Complete the following steps and submit screenshots of the executed commands (at least 10 commands) in a compressed folder.

If you still have a copy of the Git-Practice-Ch1 from Exercise 1-2, skip to step 3. Otherwise, start at step 1.

1. Navigate onto the Desktop.
2. Run the "git clone" command to copy the repository at <a href="https://github.com/CS-STech/Git-Practice-Ch1">https://github.com/CS-STech/Git-Practice-Ch1</a>. Refer to p 28 for an example.
3. Create a new file SoftwareCourses.txt in a text editor (such as Sublime) and add the following lines:
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
4. Run the "git status" command.
5. Run the command to delete EmptyFile.txt.
6. Run the "git status" command. All file names should be in red.
7. Use the "git add" command to stage the changes made to SoftwareCourses.txt, and only SoftwareCourses.txt.
8. Run the "git status" command to make sure you're prepared to commit. SoftwareCourses.txt should be green.
9. If everything looks correct, commit the changes with an appropriate message.
10.Use the "git rm" command to stage the changes made to EmptyFile.txt.
11. Run the "git status" command to make sure you're prepared to commit. EmptyFile.txt should be green.
12. If everything looks correct, commit the changes with an appropriate message.
13. Run the "git log" command. At the top of the results should be your commit to add SoftwareCourses.txt and remove EmptyFile.txt.
14. After successful completion of the previous steps, take a screenshot of the terminal showing the commands for steps 4-13.
