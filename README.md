# A tutorial on Git and Github
Hello Controllers, welcome to the tutorial on Git and Github. In this tutorial, we would look 
at a few common git workflows for a quick and easy way to collaborate/backup your code. 

## What is Git?
Git is a version control system that allows you to track changes to files. It is a distributed
version control system, which means that the entire codebase and history is available on every
developer's computer, which allows for easy branching and merging.

## Why use Git over Google Drive/Dropbox ?
Git is a version control system, which means that it keeps track of all the changes made to a file.
This allows you to easily revert to a previous version of the file if you make a mistake. It also
allows you to easily collaborate with others on the same codebase.

## Git Terminologies
- **Repository**: A repository is a collection of files and folders that are tracked by Git.
- **Commit**: A commit is a snapshot of the repository at a particular point in time. It is a 
  collection of changes to the repository.
- **Branch**: A branch is a parallel version of the repository. It allows you to work on a
    particular feature without affecting the main codebase. Once you are done with the feature,
    you can merge the branch back into the main codebase.
- **Merge**: Merging is the process of combining two branches together. It is usually done when
    you are done working on a feature and want to merge it back into the main codebase.
- **Pull Request**: A pull request is a request to merge a branch into the main codebase. It is
    usually done when you are done working on a feature and want to merge it back into the main
    codebase.
- **Fork**: A fork is a copy of a repository. It allows you to make changes to the repository
    without affecting the original repository. It is usually done when you want to contribute to
    an open source project.
- **Clone**: A clone is a copy of a repository in your local machine.
- **Push**: Pushing is the process of uploading your changes to the remote repository.
- **Pull**: Pulling is the process of downloading the changes from the remote repository.


## Git actions using FAQs
### How to create a repository from existing codebase ? 
#### Naive way
1. Create a new repository on Github.
2. Clone the repository to your local machine.
3. Copy the codebase into the cloned repository.
4. Commit and push the changes to the remote repository.
#### Better way 
1. Using Github Desktop, choose the option to create a new repository from existing codebase. 
2. Choose the codebase and the location of the repository.
3. Commit and push the changes to the remote repository.

### How to make changes your supervisor told you to make, but you are not sure if it will work ?
1. Create a new branch.
2. Make the changes.
3. Commit and push the changes to the remote repository.
4. Create a pull request to merge the branch into the main codebase.
5. Wait for your supervisor to review the changes and merge the branch.

### How to ignore some files from being tracked by Git ?
1. Create a file called `.gitignore` in the root directory of the repository.
2. Add the names of the files/folders you want to ignore in the `.gitignore` file.
3. Commit and push the changes to the remote repository.

Common gitignore files can be found here [Gitignore Files](https://github.com/github/gitignore/tree/main)


<!-- ### How to revert to a previous version of the codebase ?
1. Find the commit hash of the commit you want to revert to.
2. Run the command `git reset --hard <commit hash>`.
3. Run the command `git push --force`. -->










## Assignment


1. Fork the repository
2. Create a file in the `Attendance` folder with your name as the filename. In that text file, write your name and how you plan on using Github in your research journey.
3. Commit and push the changes to the remote repository.
4. Submit a Pull Request to merge the changes into the main repository.









## 



