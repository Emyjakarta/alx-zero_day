# GIT

## Source Code Management

**Source Code Management** can also be referred to as __Version Control__. It is a means of tracking and managing codes. In other words, the process by which __developers__ track and manage their codes is called **Source Code Management**.

## Git

Simply put, **Git** is the software that enables **developers** to perform **Version Control**.

## GitHub

**Github** is the web based platform that allows developers to perform version control. It provides a range of features like version control, collaboration, code review etc.

## How To Create A Repository

The steps below provide a basic guide on how to create a repository:

Creating a repository typically involves using a platform like GitHub, GitLab, Bitbucket, or another Git hosting service. Here, I'll outline the general steps for creating a repository on GitHub as it's one of the most widely used platforms for hosting Git repositories:
* If you don't already have one, go to the GitHub website [https://github.com/](https://github.com/) and sign up for a free account. You'll need an account to create and manage repositories. 
* Log In:
Log in to your GitHub account using your username and password.
* Access Your Dashboard:
After logging in, you will be directed to your GitHub dashboard.
* Create a New Repository:
To create a new repository, click the "+" icon in the upper right corner of the GitHub dashboard and select "New repository."
* Fill in Repository Details:
You'll be taken to a page where you can provide information about your new repository:
 * Repository name: Choose a unique and descriptive name for your repository.
 * Description (optional): Add a brief description to explain what your project or code repository is about.
 * Visibility: Choose between "Public" (visible to anyone) or "Private" (visible only to you and collaborators). Note that private repositories may require a paid GitHub subscription.
 * Initialize this repository with a README: You can select this option to create an initial README file for your repository. It's a good practice to provide basic information about your project in this file.
* Choose a License (optional):
You have the option to add an open-source license to your repository. This step is optional but highly recommended if you want others to use or contribute to your code. GitHub provides a list of common open-source licenses to choose from.
* Add .gitignore (optional):
You can also choose a .gitignore file template based on the programming language or framework you're using. A .gitignore file specifies which files and directories should be excluded from version control.
* Add a README (optional):
If you didn't select the option to initialize your repository with a README, you can create one later by clicking the "Add a README" button on your repository's main page.
* Create Repository:
Once you've filled in the necessary details, click the "Create repository" button.

Your repository is now created, and you'll be redirected to its main page. From here, you can start adding code, files, and documentation to your repository, and you can also invite collaborators to work on the project with you.

Keep in mind that the steps may vary slightly if you're using a different Git hosting platform, but the general process of creating a repository is quite similar across platforms.

## README

__README__ is basically a text file that provides important information and documentation about a code, project or repository. 

## How To Commit
Committing changes in Git is a basic operation that records your changes to the local repository. To commit changes, you'll need to use Git's command-line interface or a Git GUI client. Here's how you can commit changes using the command line:
1. Navigate to Your Git Repository
Open a terminal or command prompt and navigate to the directory where your Git repository is located. You can use the `cd` (change directory) command to navigate to your project's root directory:
	`cd /path/to/your/repository`
2. Check the Status
Before committing, it's a good practice to check the status of your repository to see what changes have been made and which files are ready to be committed. Use the following command:
	`git status`
This command will show you a list of untracked, modified, and staged files.
3. Stage Your Changes
To commit changes, you need to stage them first. Staging means selecting the changes you want to include in the commit. You can stage specific files or all changes. To stage specific files, use:
	`git add fileA fileB ...`
To stage all changes, use:
	`git add .`
Replace fileA, fileB, and so on with the actual names of the files you want to stage. The `.` notation is a shorthand for staging all changes in the current directory and its subdirectories.
4. Commit Your Changes
Once your changes are staged, you can commit them with a descriptive message using the git commit command:
	`git commit -m` "Your commit message"
Replace "Your commit message" with a concise and meaningful description of your changes. A good commit message should explain why you made the changes and what they accomplish.
5. Verify Your Commit
	`git log`
This command displays a list of commits, including the commit message, author, date, and a unique commit identifier (hash). Your most recent commit should appear at the top of the list.

That's it! You have successfully committed your changes to your local Git repository. To push these changes to a remote repository (like GitHub), you'll use the `git push` command. This step is important if you want to share your changes with others or back up your work online.
