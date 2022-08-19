# git-practice
Contains files for practicing Git 

# Part 1
## Making Commits
Commits are the most basic usage of Git. Commits let you make "checkpoints" in your code. 

After you are satisfied with your changes, you need to "stage" your changes. You *must* stage your changes before you commit!

In most real-world cases, you will stage *all* your changes at one time and then commit. To do that, you use ```git add .```. This will stage all files that have changes!

>Note: the ```.``` means "all files and folders in the current folder"

In some cases, you might want to commit only one file or a few files at one time (this is usually a rare case). You can stage individual files like this:
```
git add <filename>
```

If you want to confirm the currently staged files before you commit:
```git status```

Now you are ready to commit! 99% of teams add a special comment to each commit, this is called a commit message. Make a commit with a message with this command:
```git commit -m "Add a new button on the homepage"```

### Basic Git Summary
```
(make changes)
git add . 
git status 
git commit -m "This is a commit message"

git log //check commit history, use --oneline option for an easy-to-read log
```
# Part 2
## Assignment
1. Add 3 names to ```names.txt``` and make one ```commit``` for each name.
2. 
