# Lab 4 — Git & GitHub

## Question 1
`--global` means the Git configuration applies to my user account across all repositories on this computer. Without `--global`, the setting would apply only to the current repository.

## Question 2
Running `ls -a` showed the hidden `.git` directory, which did not appear with a normal `ls`. This directory stores the repository's Git information and history.

## Question 3
Git showed my existing files and folders as untracked files that it could start tracking. It also showed `.DS_Store`, which is a macOS-generated file and was not written by me.

## Question 4
After creating `.gitignore`, `.DS_Store` disappeared from the untracked files shown by `git status`. Git now ignores it because `.DS_Store` is listed in `.gitignore`.

## Question 5
`.gitignore` itself should be committed, not ignored. This allows the repository to remember which generated or unnecessary files should not be tracked.
