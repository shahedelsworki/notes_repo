# Notes
## Git

Git is a free open-source **version control system**, that tracks changes in computer files – code and saves them in a database called repository (projects).

* Distributed VCS: Coordinates work between multiple developers 
  * Each developer has a copy of the project and its history locally and can synchronize it with the other developers
  * Many developers can work on the same project without being on the same network
* Shows and keeps track of history of the code and takes snapshots by using a “commit”-command 
  * who made what changes when and why
  * reverts to previous versions of code at anytime
* Work on local repo and upload it on remote repo (GitHub, BitBucket etc.)

### Important terms

-	**Directory** - Folder
- **Terminal/Command line** - interface where you can type in text commands
  -	navigate around files and folders
  - create files
  - change and update
  - install and run programs
-	**CLI** - command line interface (= typing a command line + clicking [ENTER], instead of e.g.: double clicking on a folder/file to open it)
-	**cd** - change directory (=navigate between folder in the system)
-	**Code Editor** - place to write code (e.g.: Word Processor for writing code)
-	**Repository (repo)** - project, or the folder/place where your folder is kept
-	**GitHub** - a website where you host/upload all your repos online

### Git Commands

- **init** - initialize local Git repository – creates a (dot)git folder
- **clone** - bring a repo that is hosted online (e.g.: GitHub) into a folder on your local machine
-	**add** - track your files and changes in Git
-	**status** - checks status of your directory
-	**commit** - saves your files in Git
-	**push** - upload Git commits to remote repo. Like GitHub
-	**pull** - download changes from remote repo to your local machine (opposite of push)

_**Repos**_ can be created locally on your machine or on online editors in GitHub website.


## GitHub

GitHub is a **coding hosting platform for version controll and colabration**. It allows developers to work together on the same project from anywhere.

This platform allows you to create repositories, branches, commits, and Pull requests.

### Repository

Repositories are used to **organise projects**. They can contain: folders and files, images, videos, spreadsheets, and data sets. It is always recommended to include a *README* or a file with all the information about the project.

#### To create a new repository

1. In the upper right corner, next to your avatar or identicon, click **+** and then select **New repository**.
2. Name your repository.
3. Write a short description.
4. Select **Initialize this repository** with a README.md
5. Click **create repository**.

### Branch

Branching is a way to work on different versions of the a repo at one time. Branching creates a **copy of a repo** and the edits on one branch are independent of the work on other branches, such as the `main` branch (main code repository).

A new branch that is created is called `feature`.

It is mostly used for **parallel development** when working on a new feature or fixing a bug, since it allows a developer to work non-destructively.

Once a change is tested and ready, it is then merged into `main`.

#### To create a new branch

1. Go to your chosen repository.
2. Click the **drop down** at the top of the file list that says branch: `main`.
3. Type a branch name into the **new branch** text box.
4. Select the blue **Create branch** box or hit **[ENTER]** on your keyboard.

### Commits

Each saved changes are called **commits**. Once the changes are made a brief description - a **commit message** has to be written, explaining why those particular changes where made. So that the other developers working on this project can understand what was done and why.

#### Make and commit changes

1. Click on the file you want to make changes in.
2. Click the **pencil icon** in the upper right corner of the file view to edit.
3. In the editor, make the changes you need.
4. Write a commit message that describes your changes.
5. Click on the **Commit changes** button.

### Pull request

Pull requests are often used when working in teams. Once a commit is made, the developer opens a Pull request. This notifies the other developers/team members that change has been made by a certain developer and that they are requesting someone to review and test that change.

As soon as the commit is review and tested, it can either be merged by the developer that opened the Pull request or by the team member that reviewed it.

#### Open a Pull request

1. Click on the **Pull Request** tab, then from the Pull Request page, click the green **New Pull Request** button.
2. In the **Example Comparisons** box, select the branch you want to open a Pull Resquest with, to compare with the `main` branch.
3. Make sure the changes in the commit are the ines you want to submit.
4. Click on the big green **Create Pull Request** button.
5. Give your Pull Request a title and brief description.
6. Click **Create Pull Request**

### Merge

This is the final step, after reviewing and testing the changes - you can merge the `feature`branch into the `main`branch.

#### Merge your Pull Requests

1. Click the green **Merge pull request** button to merge the changes into `main`.
2. Click **Confirm merge**.
3. Go ahead and delete the branch, since its changes have been incorporated, with the **Delete branch** button in the purple box.


