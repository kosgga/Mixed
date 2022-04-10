### GIT

-Git is a "Version Control Software"<br>
-Git is also "Open Source"<br>
-git-scm.com for documentation<br>

### GITHUB 

-Collaboration website that interacts with Git<br>

----------


### GITHUB WORKFLOW

1.Branching: All of the code that was in production is on  a branch called 'master'.We don't ever want to make changes directly on to 'master'.First thing we need to do is creating an another branch.<br>
2.Commits<br>
3.Pull&Requests<br>
4.Collaborate<br>
5.Merge<br>


------


### GITHUB OPEN SOURCE WORKFLOW

1.**Fork:** Exact copy of Repository, under your account.<br>
2.**Github Flow**<br>
3.**Pull Requests**<br>


**SHA1-Hash: **  Secure Hashing Algorithm


----------


### CLONING REPOSITORIES

<ul>
  <li>What is <b>working locally?</b><br>
  When you are working on github.com you are working totally on what is called "remote repository"</li>  
</ul>



### GIT COMMANDS(Command line)

+ **git clone** This is how you clone a repository down your local machine
+ **git pull**
+ **git branch**
+ **git checkout** Any commits that are made we want them to be on that specific branch
+ **git status**
+ **git add**
+ **git commit**
+ **git push**


  
  
 -------------------------
 
 ### WHAT IS A COMMIT?
 
 + Commit is a Snapshot
 + 40 Character SHA1-hash
 + Includes blobs and metadata
 + **Commit Id's are very important**


--------------


**Secure Hashing Algorithm sha1-hash** <br>

----------

### WHY WE NEED 2-STEP COMMIT?

Any files in the working directory, if you want them to be included in the commit you need to use "git add" first.Once they are in the staging area after that once you run "git commit" and snapshot is created with sha1-hash coding.



--------


### GIT MERGE

In the Github workflow You create a branch, you make commits.Merge is used for bringing your changes back into master branch.
+ Remote(Github.com)
+ Local(git merge)


------------



### GIT&GITHUB REBASING

It is used for making your change history more linear.(time)



----------

### MERGE CONFLICTS

Easy way to solve conflicts is using "git status".


------------



### UNDO COMMITS?


+ git revert: When you revert  you're not technically  undoing the commit you are actually creating a new commit with exact opposite changes  of whichever  commit you'd like to undo. This means the commit id remains unchanged
+ git reset
+ commit --amend: Change the word that you use in a commit message
+ cherry-pick:it changes the commit id



----------







 
 
 
 




