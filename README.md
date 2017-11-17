# Version Control

## What is Version Control
In the simplest form, version control is a way to keep records of the changes to your program overtime. It is a common way for software engineers work on projects incrementally.

## Popular Version Controls
There are many types of version controls. Here are a list of a few of the most popular

- [Git](https://en.wikipedia.org/wiki/Git)
- [SVN](https://en.wikipedia.org/wiki/Apache_Subversion)
- [Mercurial](https://en.wikipedia.org/wiki/Mercurial)

Follow the links to learn more about the different version control options.

For our Soul Encoded tutorials, we will be focusing on Git.

## The Problem And Solution
Here is a simple example of what problem Git solves for software engineers.

Step 1: A engineer writes and saves the code.
Step 2: A engineer changes the code and saves over his previous changes
Step 3: A engineer realizes that he actually needs the changes that he saved over.

If we did not have version control for this example we would not have access to the code that we saved over.
So the first problem that Git solves for us is providing a **history**

With Git, we can go back to the previous point we committed to our history.

Another big problem that Git solves is dealing with collaborations between many engineers. Imagine for a moment if you and I started writing a essay together, and we are both working on the same section of the essay. Eventually we would need to **merge** our work together in a smart and precise way. Git solves this problem for us.

## Essentials

In this section we will go over the bare essentials you need to work on Soul Encoded challenges.

### Terminologies and Concepts

When working with git there are a few terminologies and concepts that you need to understand

- **Staging**: For all changes that are made they will be either un-staged or staged. This means, that they are either ready to be committed or not yet ready to be committed
- **Committed**: This is essentially saving the staged changes, but it also creates a node
- **Nodes**: a node is a unique point in time in our git history.  

a general work flow would be as follows.

Step 1: A engineer writes and saves codes.
Step 2: A engineer adds the saved changes to the staging area.
Step 3: A engineer will commit does changes and thus creating a node in our history, this also clears the staging area.

- **Branching**: The best way I can describe branching is with a multiverse example. Imagine a timeline where someone starts a alternate universe. Branch is essentially creating a new universe in our git history.

- **Merging**: Merging used to merge the two branches back into one branch. One note is that when you initialize git into your project, you create a default **master** branch.


### Most common commands
`git init`: Initializes git control of your project.

`git status`: Displays which files have been changed and which files are currently in the staging area.

`git add`: Adds saved changes to the staging area.

`git commit`: Creates a node in our git history with all the saved changes in the staging area.

`git log`: Displays our git history and all nodes.

`git checkout`: creating and jumping into new branches.

`git branch`: manage your branches

`git merge`: Combines two branches into one.

These are just some of the basics that you will need to complete the below challenge but feel free to dig through the [Official Documentations](https://git-scm.com/doc). A firm understanding of git is vital to your journal to become a software engineer.

## Github vs Git
So a lot of new engineers get confused by Git vs Github. We will go over Github in the next sections, but basically Github is a web based version control service that hosts your projects in a online repository.

In simple terms, Github can save your project online in a repository, then you can use Git to make changes to your repository.

Most importantly, Github uses Git. Github has a few additional commands that you will need to learn in the next section.

## Challenge

Prerequisites for this challenge
- [IDE](https://github.com/SoulEncoded/IDE)
- [Command Line]()

In this challenge do the following:

1. Create a new project in your workspace and initialize git control
2. Create a new javascript file and add `console.log('hello');` to the first line
3. Commit these changes
4. Create and Checkout a new branch
5. Reopen the javascript file and change the code on the same line to `console.log('new branch');`
6. Merge this new branch back into your master
7. Resolve your merge conflicts and make one final commit with the changes from the merge.

With these steps you have gone through a major work flow using git.
