Answer 1
git version 2.24.3 (Apple Git-128)

Answer 2
credential.helper=osxkeychain
user.name=AL-Husain Bani Oraba
user.email=hb407717@ohio.edu

Answer 3
There are so many instructions that came out as a result of "git add --help". The "DESCRIPTION"" section explains a lot of commands and their function. Also, the "options" sections has a lot of instructions about adding files and so one. The result also provide some examples.

Answer 4
MacBook-Pro-alkhas-b-alhsyn:git-lab alhusainbanioraba$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
    README.md
    answers.md

nothing added to commit but untracked files present (use "git add" to track)
MacBook-Pro-alkhas-b-alhsyn:git-lab alhusainbanioraba$ 

Answer 5
MacBook-Pro-alkhas-b-alhsyn:git-lab alhusainbanioraba$ git add README.md
MacBook-Pro-alkhas-b-alhsyn:git-lab alhusainbanioraba$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
    new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
    answers.md
    
    Answers 6
    MacBook-Pro-alkhas-b-alhsyn:git-lab alhusainbanioraba$ git status
    On branch master

    No commits yet

    Changes to be committed:
      (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md
        
        
    Answers 7
    On branch master
    Changes not staged for commit:
      (use "git add <file>..." to update what will be committed)
      (use "git restore <file>..." to discard changes in working directory)
        modified:   answers.md

    no changes added to commit (use "git add" and/or "git commit -a")
    MacBook-Pro-alkhas-b-alhsyn:git-lab alhusainbanioraba$ 
    
    Answers 8
    no changes added to commit (use "git add" and/or "git commit -a")
    MacBook-Pro-alkhas-b-alhsyn:git-lab alhusainbanioraba$ git log
    commit 679a58614125d20b6c6e57efb3d16e7a7a7ff3cc (HEAD -> master)
    Author: AL-Husain Bani Oraba <hb407717@ohio.edu>
    Date:   Wed Sep 2 16:50:31 2020 -0400

        Initial commit

    Answers 9
    error: src refspec maste does not match any
    error: failed to push some refs to 'https://github.com/banioraba/git-lab.git'
    MacBook-Pro-alkhas-b-alhsyn:git-lab alhusainbanioraba$ git push -u origin master
    Username for 'https://github.com': banioraba
    Password for 'https://banioraba@github.com': 
    Enumerating objects: 4, done.
    Counting objects: 100% (4/4), done.
    Delta compression using up to 8 threads
    Compressing objects: 100% (3/3), done.
    Writing objects: 100% (4/4), 769 bytes | 769.00 KiB/s, done.
    Total 4 (delta 0), reused 0 (delta 0)
    To https://github.com/banioraba/git-lab.git
     * [new branch]      master -> master
    Branch 'master' set up to track remote branch 'master' from 'origin'.
    MacBook-Pro-alkhas-b-alhsyn:git-lab alhusainbanioraba$ 

Answers 10
no
 
 Answers11
 an error
 
 Ansewer 12
the class section "CS 2400, Section 107" is showing up
 
 Ansewer 13
 
 .        ..        .git        .gitignore    README.md
 MacBook-Pro-alkhas-b-alhsyn:git-lab2 alhusainbanioraba$ 
 
 anse
 
 
