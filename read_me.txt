# Adding user name and email to global list
git config --global --list
git config --global user.name "Jenesanne"
git config --global user.email jenesanne@gmail.com

# Initializing git commit
git init
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/jenesanne/hello.git
git push -u origin main

# when all else fails go to the beginning
https://kbroman.org/github_tutorial/pages/first_time.html # Your first time with git and github
git config --global user.name "Jenesanne"
git config --global user.email jenesanne@gmail.com
ssh-keygen -t rsa -C "your_email@example.com"
pbcopy < ~/.ssh/id_rsa.pub
ssh -T git@github.com

# Adding a branch
git checkout -b <name>

# Switching between main and new branch
git checkout <name> / git checkout main

# creating a git pages
#create new repo
#call it:
jenesanne.github.io

# Make changes to files and commit them to github
# go to settings and find pages and click on the link for repo
# will bring you to the website updated as its seen

