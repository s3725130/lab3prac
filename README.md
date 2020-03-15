# SOFTWARE ENGINEERING FUNDAMENTALS Lab #1: Git 

### Time 30 minutes



## Introduction
This assessment evaluates the following CLOs:

- CLO 2: use appropriate design, version control and collaboration tools to work effectively as a team.
- CLO 4: implement the system using appropriate tools and techniques

The following topics are assessed:

- Basic Git Use.



## PART 1. Initial Setup
Open your git console, and perform the following commands to complete the set up for the lab. You have 5 minutes to do this.

Clean your history. This will close you shell and you can reopen after.

```
$ history -c && exit
```

Then, open another Git command, and perform the following:

**You must use your RMIT University email account.**

```
git config --global user.name “[firstname lastname studentID]”
git config –-global user.email “sxxxxxxx@student.rmit.edu.au”
git config –-global color.ui auto
git config core.hooksPath .githooks
```

_You **must** complete the assignment using the Git console only. Evidence of this will be submitted in the last step._



## PART 2.  Work and Solve It!
**Everything needs to be solved using command console _only_. Evidence will be submitted in the last part. If you don't use console, you won't pass the assignment**.

### IMPORTANT

* Commit messages must be appropriate and will impact you marks.
* **DO NOT FORGET TO PUSH ALL YOUR CHANGES TO GITHUB WHEN YOU ARE DONE**
* Tasks are independant from each other. You are free to complete them in any order.


### Task 1

1. Move to the branch `task1`
1. Track the changes with git

### Task 2

1. Move to the branch `task2`
2. Identify the file that has been modified and reset to its original state.


### Task 3

1. Move to the branch `task3`
2. Files have been staged
3. Reset to its original state.

### Task 4

- Create a branch from master called `task4`
- Send the new branch to the remote server

### Task 5

- Move to `task5` branch
- Incorporate to branch `task5` the changes in the `t5-changes`.

**TIP**: Don't execute commands blindly. 




## PART 3. Console Log Evidence
You need to submit the evidence that you used the Git console to solve this. Submitting this is mandatory.

3.1 Make sure you are on the `master` branch.

3.2 Perform the following commands:


```
$ history >> command_history.txt
```

3.3 A new file named `command_history.txt` should be in your project's root directory. Make sure you commit this file, and upload it to the remote `master` branch.

### FAILING TO SUBMIT COMMAND HISTORY WILL RESULT IN FAILING THE ASSESSMENT

### DO NOT FORGET TO PUSH ALL YOUR CHANGES TO GITHUB

## Rubric

* NN: Completed less than 2 tasks OR not provided evidence requested in PART 3
* PASS: Completed at least 2 tasks
* CR: Completed at least 3 tasks
* DI: Completed at least 4 tasks 
* HD: Completed all tasks

NOTE: If you commit messages are not appropiate, the task will be consedered as incomplete.

* Correct Message: "Fix typo in introduction to user guide"; "Finished task 1"
* Incorrect Message: "more code"; "some changes", "done"


## Copyright Acknowledgements

Original code used in this assessment is publicly available under the MIT License: https://github.com/eugenp/tutorials

You are not allowed to distribute or share the Assessment material.
  
