# github-practice-repo

**#######Follow this steps to get cypress tests running#######**

**install node.js and npm:**
https://nodejs.org/es/download/
once installed, confirm it is successfully installed by using this in command line: node -v

**install git locally:**
https://git-scm.com/download/win

create new folder locally with any name you want (i.e github-practice-project)

**open cmd and navigate to newly created folder**

initiate git:

git init

clone remote repo to the local file:

git clone https://github.com/Olavarry/github-practice-repo.git

Set your git hub account:
git config --global user.email {yourEmailassociatedToGitHub} 
git config --global user.name {yourName}

install dev dependencies:

npm install

verify "node modules" folder should be added to the project.

open cypress:

npm run cypress:open
      
you should be able to select test to run in cypress GUI

**How to create feature branch:**

git checkout -b feature/{NameofYourbanch}

**How to change to master/feature branch**

git checkout master
git checkout {NameOfYourFeatureBranch}
