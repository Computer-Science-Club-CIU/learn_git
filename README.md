# Git Learning Repository - Attendance Task

Welcome to the Git Learning Repository! This repository is designed to help you learn the basics of Git through a simple attendance task. Follow the instructions below to get started.

## Setup git on your computer if you have not done so

1. Download Git from [this link](http://git-scm.com/downloads)
2. Register for github from [this link](https://github.com/)
3. Set up git on you computer with the steps below
   `git config --global user.name "Firstname Lastname"`
   `git config --global user.email "your_email@youremail.com"`
4. Create a new access token for authenticating with github from [here](https://github.com/settings/tokens/new)

## Instructions

1. Clone the Repository:
   `git clone https://github.com/Computer-Science-Club-CIU/learn_git.git`
   The `git clone` command is used to create a local copy of the repository on your machine.

2. Create a New Branch: `git checkout -b <branch-name>`
   Create a new branch using the `git branch` command and switch to it using `git checkout`. Replace `<branch-name>` with a descriptive name for your branch (in this case your name).

3. Append Your Name:

- Open the `attendance.txt` file in a text editor.
- Append your name to the file, following the existing format.
- Save the changes.

4. Commit and Push:

- `git add attendance.txt`
- `git commit -m "Add my name to attendance"`
- `git push origin <branch-name>`
  Use the `git add` command to stage the changes made to the attendance file. Then, use `git commit` to create a commit with an appropriate message. Finally, use `git push` to push your branch to the remote repository.

5. Review and Merge:

- Once you've pushed your branch, the repository I will review your changes.
- If everything looks good, your branch will be merged into the main branch or an appropriate branch.

##Explore Further:
This attendance task covers the basics of cloning, branching, committing, and pushing changes to a Git repository. However, Git offers many more powerful features. Take this opportunity to explore and learn more about Git on your own.

If you have any questions or need assistance, feel free to reach out to the repository owner or any available mentors. Happy learning!

## Resources

Here are some helpful resources to further enhance your understanding of Git:

- [Git Documentation](https://git-scm.com/doc): Official documentation for Git.
- [Git - The Simple Guide](https://rogerdudler.github.io/git-guide/): A concise guide to Git with clear explanations and examples.
- [Atlassian Git Tutorials](https://www.atlassian.com/git/tutorials): Comprehensive tutorials and guides on Git from Atlassian.
