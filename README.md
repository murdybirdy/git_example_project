This is a repo for learning git

# Git and Git comments

## what is Git?
 - version control for projects/applications

 ## why is Git useful?
 - Allows us to work on projects that require a lot of work while keeping track of hte changes we've made along the way
 - We can also work solo or with many people
 - Git provides a way for everyone to access a project, work on it simultaneously, and update each other with the changes.

 # Git basic commands
  # Git Push
    - git init
      - initializes a local git repository
    - git remove -v
      - returns the remove repo url in the CLI
    - git remote add orign <url>
      - adds a remot repo url to the local git repo

    - git status
      - prints out current modified files
      - if files are red, that means they are UNSTAGED (not ready to be committed)
      - if files are green, that means they are STAGED (ready to be committed)

    - git add .
      - stages all files / changes

    - git add <file name (e.g. index.html)>
      - stages one file at a time

    - git commit -m 'relative message about the commit'
      - commits are basically snapshots of our code at the time we make the commits
      - only exist locally unitl we push the changes up to github

    - git push -u origin <branch-name (e.g main)> 
      - -u means make what follows ("origin main") the default statement; later "git push"s will push to the same place
      - push to the origin url
      - push to the main branch

  # Git Pull
    - git pull
      - pulls down a copy of the remote repo; changes made in github

  - git log
    - checkpoints/snapshots of our project; timestamps and authors of changes, a log of commits
    - can browse through the project at theh time of a specific commit using its long alphanumeric commit tag

  - "q" to get out

  - git clone <repo-url>
    - clones a remote repo onto your local machine
    - automatically creates a new folder by the name of the repo itself
    - we can specify the name of this folder if we wanted to
    - ex: git cloen <repo-url> <new-folder-name-to-clone-into>



- In VS Code, yellow file name in the Explorer with "M" means modified,
  green file name with 

 - 'touch' means add file (e.g. touch index.js)
 - echo <"text in quotes"> >> <filename (e.g. README.md)>
  - writes text to a file through the terminal
  - e.g. echo "This is a repo for learning git" >> README.md