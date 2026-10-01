# Lab 4 Notes

## Question 1
`--global` means the setting applies to all Git repositories on my computer. Without it, the setting would only apply to the current repository.

## Question 2
`.git` appeared when I used `ls -a`. It contains the files and information Git uses to manage the repository and its history.

## Question 3
Git was showing the files and folders inside the `coding-cafe` folder. The `.venv` folder looked like something I did not write because it contains Python environment files.

## Question 4
After adding `.gitignore`, the `.venv`, `__pycache__`, `.pyc`, and `.DS_Store` files disappeared from `git status`. Git is now ignoring them.

## Question 5
`.gitignore` should be committed. It tells Git which files should be ignored in the repository.

## Question 6
`README.md` moved from "Untracked files" to "Changes to be committed". This means I added it to the staging area using `git add`.

## Question 7
Git printed that the commit was created and showed the files that were changed. The exact number depends on the files in my folder.

## Question 8
The first seven characters are part of the commit hash. They are used to identify a particular commit.

## Question 9
The four steps are edit, stage, commit, and repeat. We make a change, use `git add`, use `git commit`, and then repeat.

## Question 10
`README.md` has a special name because GitHub automatically displays it on the repository's main page. It gives people basic information about the project.

## Question 11
`gh auth login` logged me into GitHub through the terminal. This means GitHub can remember my authentication when I push.

## Question 12
The `README.md` file is shown on the GitHub front page. GitHub automatically displays it because it is named `README.md`.

## Question 13
No, pushing did not change my local history. It only copied my commits to GitHub.

## Question 14
A private repository exists on GitHub but only people with permission can see it. If a repository does not exist on GitHub, there is no online repository to access.
