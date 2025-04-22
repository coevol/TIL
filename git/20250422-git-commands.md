Git commit and branch commands

---------------------------------------------

After you download and install Git Bash,

Setting up configuration inside ~/Documents/dev folder.

@ git bash terminal 

~/Documents/dev

$ git config --global core.pager "cat"

$ git config --global core.editor "vim"

$ git config --list

$ git config --global user.name "coevol"

$ git config --global user.email "rpajhc@gmail.coml"

$ git config --list

$ vim ~/.gitconfig

##################


Sign up and log in GitHub

user name : "coevol"

Create a new project "my-first-repo"

GitHub > Create a new repository > Code Clone

Fill in a project name

Readme.md checked

MIT License selected

##################


GitHub project Code > Copy URL

$ git clone https://github.com/coevol/my-first-repo.git

##################


vim text-file > git add > git commit > git push

vi text-file > git add text-file > git commit > git push origin main

##################


$ git add TEXT-FILE

$ git commit

Update commit history

$ git push origin main

Before committing local changes to remote git repository , a personal access token must be generated.

Generate a personal access Token

ex) Fine-grained personal access tokens vs Tokens (classic)

On the upper right Profile Photo > Settings > Left side slide menu "Developer settings" > Personal access tokens 

> select either "Fine-grained tokens" or "Tokens(classic)" > Generate new token

##################


Git commit history file

Logging Convention

a brief phrase or clause rather than a full sentence

contents :

prefix example: 

feature, 

build, 

fix, 

docs, 

style( such as code format change),

test-related change,

breaking changes,

configuration,

refactor,

chore,

etc.

##################


Readme.nd 파일 만들기 샘플

https://rahuldkjain.github.io/gh-profile-readme-generator/

##################


.gitignore 

https://www.toptal.com/developers/gitignore/

##################


Git branch : Sub space 

Git commit : repository timeline change history

$ git branch

$ git branch NEW-BRANCH-SPACE

$ git switch NEW-BRANCH-SPACE (checkout is deprecated, instead switch or restore is used)

modifying text files ...

$ git switch main

$ git merge NEW-BRANCH-SPACE

$ git branch -d NEW-BRANCH-SPACE

##################


vim editor key commands

"ESC" --> normal mode

        "I" --> insert mode
        
        "v" --> visual mode
        
        ":" --> command mode  >  :w, :q, :wq, :w!, :q!, ...
        


