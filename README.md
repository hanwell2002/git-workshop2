# git-workshop2

 eval "$(ssh-agent -s)"

 git config --global --add safe.directory E:/bootcamps/GITWORKSHOP/git-workshop2

 git push --set-upstream origin release/2022.12.17





--------------

git-workshop2

mkdir git-workshop2

cd git-workshop2

echo "git-workshop2" >> README.md

git init -b main

git add .

git branch --list

git commit -m "initial commits"

git remote add origin git@github.com:hanwell2002/git-workshop2.git

git push origin main


# 

# create new branch release/1.0.1

git checkout -b release/1.0.1              ==> git branch release/1.0.1 && git checkout release/1.0.1

# modify code and push new code to github

git add .

git commit -m "updates code"

git push --set-upstream origin release/1.0.1