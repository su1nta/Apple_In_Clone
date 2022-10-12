# Apple_In_Clone
This is a apple.com clone made using HTML, CSS and JavaScript

# What is this Repository or project about?

This repository contains an apple website clone which contains information about newly launched apple products,display best offers which customer can avail .This website aso contains information about Services,Apple store,different apple products for Business,Health and Education in footer section.

# What Technologies are used?

This website is made using HTML,CSS and JAVASCRIPT.

# How to Contribute in this Repo?

#  how to fork

A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project.

STEPS TO FORK A REPOSITORY

1. On GitHub.com, navigate to the octocat/Spoon-Knife repository.
2. In the top-right corner of the page, click Fork(Fork button).
3. Select an owner for the forked repository.
4. Create a new fork page with owner dropdown emphasized
5. By default, forks are named the same as their parent repositories. You can change the name of the fork.
6. Optionally, add a description of your fork.
7. Create a new fork page with description field emphasized
8. Choose whether to copy only the default branch or all branches to the new fork. For many forking scenarios, such  as contributing to open-source projects, you only need to copy the default branch. By default, only the default branch is copied.
9. Option to copy only the default branch
10. Click Create fork.


# How to clone?

1. Cloning your forked repository

2. On GitHub.com, navigate to your fork of the Spoon-Knife repository.

3. Above the list of files, click  Code.
"Code" button

4. Copy the URL for the repository.

5. To clone the repository using HTTPS, under "HTTPS", click .
6. To clone the repository using an SSH key, including a certificate issued by your organization's SSH certificate authority, click SSH, then click .
7. To clone a repository using GitHub CLI, click GitHub CLI, then click .
8. The clipboard icon for copying the URL to clone a repository with GitHub CLI
Open Git Bash.

9. Change the current working directory to the location where you want the cloned directory.

10. Type git clone, and then paste the URL you copied earlier. It will look like this, with your GitHub username instead of YOUR-USERNAME:

$ git clone https://github.com/YOUR-USERNAME/Spoon-Knife
Press Enter. Your local clone will be created.

$ git clone https://github.com/YOUR-USERNAME/Spoon-Knife
> Cloning into `Spoon-Knife`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remote: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.


# How to create separate branch?

1. Create Git branch using checkout
The easiest way to create a Git branch is to use the “git checkout” command with the “-b” option for a new branch. Next, you just have to specify the name for the branch you want to create.

$ git checkout -b <branch-name>
As an example, let’s say that you want to create a new Git branch from the master branch named “feature”

2. To achieve that, you will run the “git checkout” command with the “-b” option and add “feature” as the branch name.

$ git checkout -b feature
Switched to new branch 'feature'
As you can see, by using the “git checkout” command, you are creating a new branch and you are switching to this new branch automatically.

3. But what if you wanted to create a Git branch without switching to the new branch automatically?

Create Git Branch without switching
In order to create a new Git branch, without switching to this new branch, you have to use the “git branch” command and specify the name of the Git branch to be created.

$ git branch <branch_name>
You can later on switch to your new Git branch by using the “git checkout” function.

$ git checkout <branch_name>
Going back to our previous example, let’s say that you want to create a branch named “feature”.

$ git branch feature
You can inspect existing branches by running the “git branch” command with the “-a” option for all branches.

$ git branch -a
create git branch
Awesome, you have successfully created a new Git branch and you switched to it using the checkout command.