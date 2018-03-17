## GITHUB TUTORIAL

In this repository you will learn how to:

    * Create and use a repository
    * Start and manage a new branch
    * Make changes to a file and push them to GitHub as commits
    * Open and merge a pull request

Let’s get started with GitHub! :blush:

## What is Github?

GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

This tutorial teaches you GitHub essentials like Repositories, Branches, Commits, and Pull Requests. You will create your own  repository and learn GitHub’s Pull Request workflow, a popular way to create and review code.

<p align="center">
    <img src="https://octodex.github.com/images/octobiwan.jpg" width="100" height="100">
</p>

## 1. Create a Repository

A repository is usually used to organize a single project. Repositories can contain folders and files, images, videos, spreadsheets, and data sets – anything your project needs. I recommend including a README, or a file with information about your project. GitHub makes it easy to add one at the same time you create your new repository. It also offers other common options such as a license file.

### Create a new repository

```markdown
1. In the upper right corner, next to your avatar, click and then select **New repository**.
2. Name your repository `FirstRepository`.
3. Write a short description. 
4. Choose to make the repository either public or private. 
5. Select **Initialize this repository with a README**.
```

<p align="center">
    <img src="https://github.com/eduardomacetas/GithubTutorial/blob/tutorialv1/img/create_new_repository.png" width="600" height="450">
</p>


```markdown
#NOTE: Public Repositories are visible to the public,  
#while Private Repositories are only accessible to you, and people you share them with.  
#Your account must be on a paid plan to create a private repository. 
```

Congratulations you created your first repository :blush: :tada: :tada: 

## 2.  Create a Branch

**Branching** is the way to work on different versions of a repository at one time.

By default your repository has one branch named `master` which is considered to be the definitive branch. We use branches to experiment and make edits before committing them to master.

In the next diagram shows:
```markdown
    * The master branch
    * A new branch called **Feature** (because we’re doing `feature work` on this branch)
    * The journey that feature takes before it’s merged into master
```
<p align="center">
    <img src="https://guides.github.com/activities/hello-world/branching.png" width="850" height="250">
</p>

From [GitHub Guides: "Hello World"](https://guides.github.com/activities/hello-world/branching.png)

Use branches for keeping bug fixes and feature work separate from our `master` (production) branch. When a change is ready, they merge their branch into `master`.

### Create a New Branch

```markdown
1. Go to your repository `FirstRepository`.
2. Click the drop down at the top of the file list that says branch: `master`.
3. Type a branch name `First-branch` into the new branch text box.
4. Select the blue Create branch box or hit “Enter”.
```
<p align="center">
    <img src="https://github.com/eduardomacetas/GithubTutorial/blob/tutorialv1/img/create_branch.png" width="600" height="150">
</p>

Now you have two branches, **master** and **First-branch**. They look exactly the same, but not for long! 

Nice you created your first branch :blush: :tada: :tada: 

## 3. Make and commit changes

Great!!! Now, you are on the code view for your **First-branch branch**, which is a copy of master. Let’s make some edits.

On GitHub, saved changes are called **commits**. Each commit has an associated commit message, which is a description explaining why a particular change was made. Commit messages capture the history of your changes, so other contributors can understand what you’ve done and why.

### Make and commits changes

```markdown
1. Click the README.md file.
2. Click the pencil icon in the upper right corner of the file view to edit.
3. In the editor, write a bit about yourself
4. Write a commit message that describes your changes.
5. Click **Commit changes** button.
```

<p align="center">
    <img src="https://github.com/eduardomacetas/GithubTutorial/blob/tutorialv1/img/commit01.PNG" width="600" height="150">
</p>

<p align="center">
    <img src="https://github.com/eduardomacetas/GithubTutorial/blob/tutorialv1/img/commit02.PNG" width="600" height="150">
</p>

These changes will be made to just the README file on your readme-edits branch, so now this branch contains content that iss different from master.

Good! :blush: :tada: :tada: 

## 4. Open a Pull Request
