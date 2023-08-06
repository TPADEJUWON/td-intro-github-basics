Hi,

This is my first local repo moved to the remote repo.

Version Control

Version control, also known as revision control or source control, is a systematic approach and software tool used in software development and other collaborative projects to manage changes to files and documents over time. It enables multiple contributors to work on the same project simultaneously while keeping track of modifications, additions, and deletions to the project's files and codebase. This system helps maintain a history of changes, allows for easy collaboration,and provides mechanisms to revert to previous states or versions of the project.

What do you understanted by Git?
Git is a distributed version control system (DVCS) that is widely used in the field of software development to manage and track changes in source code and other project files.

Describe the process of committing a project to github repository.

Committing a project to a GitHub repository involves a series of steps that start with creating a local Git repository on your machine and ends with pushing your commits to the remote GitHub repository. Below are the steps to follow to commit a projet to github repository:

1. Create your project folder on your local machine and add the neccessary files
2. Open your github account and create a repository with the same name of your local project name.
3. Download and install git on your local machine
4. Configure your git with the command git config --global user.name to set your username and git config --global user.email to set your email
5. Open terminal on (mac Os), Shell on (Linux) and command prompt on (windows) or rather download Visual studio code to make it easier. visual studio code provide us with terminal through which we can commit to github.
6. on the terminal run git init to initialize git on your local machine.
7. Run git add . to add
8. run git commit -m "first commit" to commit
9. run git branch -M main to create branch main
10. run git remote add origin git@github.com:yourusername/reponame.git to create your local repo. This will prompt you for verification. Verify and goto the next step.
11. then finally run git push -u origin main. to push the local repo to your remote repo.
