# Salad
Not tasty but healthy.



user@RCR-LR0BNT1H MINGW64 ~/Desktop
$ cd Salad

user@RCR-LR0BNT1H MINGW64 ~/Desktop/Salad (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Ingrediants.md
        Recipe.md

no changes added to commit (use "git add" and/or "git commit -a")

user@RCR-LR0BNT1H MINGW64 ~/Desktop/Salad (main)
$ git add README.md

user@RCR-LR0BNT1H MINGW64 ~/Desktop/Salad (main)
$ git add Ingrediants.md

user@RCR-LR0BNT1H MINGW64 ~/Desktop/Salad (main)
$ git add Recipe.md

user@RCR-LR0BNT1H MINGW64 ~/Desktop/Salad (main)
$ git commit  -m "Salad"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'user@RCR-LR0BNT1H.(none)')

user@RCR-LR0BNT1H MINGW64 ~/Desktop/Salad (main)
$ git remote add Salad https://github.com/AdiAgr3006/Salad.git

user@RCR-LR0BNT1H MINGW64 ~/Desktop/Salad (main)
$ git push  -u Salad
Everything up-to-date
Branch 'main' set up to track remote branch 'main' from 'Salad'.
