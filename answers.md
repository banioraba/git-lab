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
