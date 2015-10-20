# Git Cheatsheet

### Start a new project

```shell
$ mkdir project_name
$ git init
$ touch readme.md
$ git add readme.md
$ git commit -m "initial commit"
```

### Do some work and then save it

First, do some work!
Make some changes, put them in the box, label the box.

```shell
$ git status
$ git add <whatever file>
$ git status
$ git commit -m "I made a bunch of changes."
```

### Share my work with the world!

First, create a github repo.

```shell
$ git remote add origin git@github.com:<username>/<name of repository>
$ git push -u origin master
```

### Help someon else with their code

First, find the code on github that you want to contribute to.

Then fork it!

```shell
$ git clone git@github.com:<your username>/<repo_name>
```
Then, make some change tou think are important.

```shell
$ git add <your files>
$ git commit -m "A really thorough explanation of what we did since this is someon else's work."
$ git push origin master
```
Finish what you started working on, then push up any additional commits.

File a pull request with the commits in it that you want to share. Make sure you have a good explanation in the pull request of what this is, what it's intended to do, and some nice language.

