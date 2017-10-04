# Git tutorial

> **Note:**
> -  This tutorial has been done for the Tampere University of Applied Science business administrator systems students who need a simple guide to git usage.
> - This tutorial was implemented to be a part of a Git training session I, [Dosentos](https://github.com/Dosentos) & [mehxit](https://github.com/mehxit) put up together for fellow students. You can find your slideshow in the repository. Unfortunately it's in Finnish.
> - To make it easier to maintain this tutorial has been uploaded to github. If there's something you would correct in this tutorial, please open new issue in the repository.  (Instructions below)

## Motivation
 In this tutorial you will learn the basics of GIT. This is not very advanced tutorial but this should get you going with GIT. You will learn to:
 - Install git
 - add and commit files
 - basics of branching
 - create a pull request
 - solve simple merge conflicts manually

First we take a brief look at the teory of how Git works. Then we'll teach the most crucial commands and finally in the end you'll have some excercises that you can do on your own.

In this tutorial we use a basic command line tool for the simpliest reason. When you learn the commands with command line, you should know every tool's gui. But if you learn to push some buttons in some tool, you only know that tool and you may encounter big problems time to time while developing.

As an example of code hosting site we use github so the terminology comes from there.

## What is Git
Common misconception is that Github is same thing as git. This is not true even though Github is sometimes referred as *git*. 

GIT is a supply chain management tool that you can download to your pc locally. Github is a web service that provides storage where you can upload your GIT repositories. So basically.. You use git in your local pc and then upload the code to github.

Github, Gitlab, Bitbucket etc. are all different services where you can upload your repository. Terminology and features may vary but they all work the same way (e.g. Pull request [github] vs Merge request [bitbucket]). 

## Three stages of Git (tai mitä tahansa mitä Eetu haluaa oman settinsä nimeks)




## Git Commands

### git init

### git status

### git commit

### git branch

### git checkout

### git push

### git pull

### git merge

### git stash


## Getting to know Github

By now you should have created yourself a github account. If you don't have github account, do it and log in to use the features explained below.

#### **Creating a repository**
In most cases you want to start project by creating a remote repository. In github you can create new repository by clicking green icon "New Repository" at the right side of the page.

It opens you new page where you can give a name and description to the repo. You can also initialize the repo with readme, license and .gitignore. All of them can be also added later so unless you know you will need them you shouldn't add them yet.

#### **Pull Requests**
You can create a pull request by going in your repository's site and selecting your working branch at the ***branch*** *dropdown* above file list at the left side of the page. After selecting the branch click **pull requests** -tab below your-name/your-repository. Then you can open new pull request by clicking green button "**New pull request**"

Now you should select where do you want your branch to be merged. **Base** means the branch where you want to have all the changes merged and **Compare** mean the branch that you have been working on where you have changes that you want to add to the base.

Now you can type a message attached to pull request. Pull request message should have a short description of what you have changed and why. In the pull request you should also either mention or tag (if possible) someone. Otherwise it's possible that no-one gets notified of your pull request and it will be just lost in Github unless someone bumps into it by accident.

#### **Issues**
Issues have their own tab below your-name/your-repo. You can open new issue just by clicking  green **New Issue** button at the right side of the page. Issues are often bug reports etc. Or questions about the code in the repository. You can disable Issues from the settings.

## Installing Git
- Download [Git](https://git-scm.com/) 
- Follow installation wizard's instructions
	- Default settings should be fine (at least on windows)

## Assignments

#### **Setup**

1. Create GitHub account
2. Create repository in GitHub
2. Install Git
4. Clone your repository

#### **Making changes**

5. Edit `README.MD` in your repository
6. Make initial commit
7. Push initial commit to remote

#### **Workflow**

8. Create branch `develop`
9. Switch to `develop` and create `index.html`
10. Make changes in `index.html`
11. Commit changes & push to remote

#### **Forking**
> **Notes:**
> - if you don't have a partner you can fork any repository on github. Just remember that in 4th exercise it's very likely that your pull request gets rejected instead of merged in the official repository. 

12. Fork your partner's repository
13. Clone your fork
13. Make changes & commit
14. Create pull request on GitHub and ask your partner to review the PR (protip: use mentions e.g. `@github-username`)
15. Merge PR

#### **#teamwork**
> **Notes:**
> - if you don't have a partner you can just skip exercise 1 and 2. Then you should act like there was two developers in the project and you create a separate branches for both and you modify the same files in both branches.

16. Create new repository or use already existing repository for you and your partner
17. Add your partner as a contributor
18. (initial commit)
19. Create separate `feature/my-feature` branches
20. Make multiple changes & multiple commits
21. Push changes to remote

#### **Merge conflicts**

22. Pull latest master branch
23. By now you might have a merge conflict
24. Resolve merge conflict (manually with text editor or use visual merge tool)
25. Push merge commit to remote

### [GitHub help](https://help.github.com)
### [Google Sheets](https://docs.google.com/presentation/d/1joNqC9FE4hQgPqa0DmG20MsHl83ebWYgZa3iLEXzl1U/edit?usp=sharing)
