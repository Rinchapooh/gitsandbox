

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


Git status - Show your working area

Working area consist with three things such as WORKING_DIRECTORY, STAGING_AREA and LOCAL_REPOSITORY

GIT add - Add files from working directory to the staging area

GIT COMMIT -m "Commit's message" - This command is add files from staging area to the local repository.

GIT PUSH - This command will replicate local repository to the remote repositiry.

------------------------------
$ git config --global user.name "Your Name Comes Here"
$ git config --global user.email you@yourdomain.example.com


git remote  remove origin
git remote add origin https://github.com/Rinchapooh/gitlesson.git


git remote add origin https://github.com/Rinchapooh/lessongit.git

git remote set-url origin <new-remote-url> | Change remote repositories's URL
git remote -v | show the remote repositories's url.


---------------------------------

git diff - Shows changes only in working directory
git diff -staged | Show changes already staget
git diff <commit>^!  - Show diff with a previous commit
git diff <from commit> <to commit> | Compare two commits
