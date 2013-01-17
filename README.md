front-end-sample
================

## Introduction

In this tutorial, replace :
- Alfred Almendra by your name
- alfredalmendra by your GitHub username (WARNING : must be lowercase)
- alfred.almendra@gmail.com by your email address
- front-end-sample by your GitHub project name (WARNING : should be lowercase)

## Install

=> Install git client : http://git-scm.com/downloads

=> See online doc : https://help.github.com/articles/set-up-git

git config --global user.name "Alfred Almendra"

git config --global user.email alfred.almendra@gmail.com

git config --get-regexp user.*

## First draft of front-end-sample

mkdir front-end-sample

cd front-end-sample

git init

git status

echo front-end-sample > README.md

echo ================ >> README.md

git add -A && git commit -a -m "Readme file"

git status

=> Create a new repository in your GitHub account : https://github.com/alfredalmendra

git remote add origin https://github.com/alfredalmendra/front-end-sample.git

git push -u origin master

git status

## Using GitHub project pages

git checkout --orphan gh-pages

echo "Hello world" > index.html

git status

git add -A && git commit -a -m "Index first draft"

git push origin gh-pages

git status

=> On GitHub website, select your repository : Repository Settings > Options > Settings > Default Branch > select "gh-pages"

git push origin :master
git branch -D master

=> Wait up to 10 minutes
http://alfredalmendra.github.com/front-end-sample

## Using a custom domain

http://mon-domaine-gratuit.fr

=> Choose your domain URL and link it to your GitHub project pages URL : http://asqss.projet.me/

