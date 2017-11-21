# Version Control

Youtube Video Of Version Control

<a href="https://www.youtube.com/watch?v=W7DxODMjt7E"><img src="https://img.youtube.com/vi/W7DxODMjt7E/0.jpg"/></a>

## What is Version Control
In the simplest form, version control is a way to keep record of changes to your program overtime. It is a common way for software engineers work on projects incrementally.

## Popular Version Controls
There are many types of version controls. Here are a list of a few of the most popular

<!-- [![Git](assets/git.png)](https://en.wikipedia.org/wiki/Git) -->
<!-- [![SVN](assets/svn.png)](https://en.wikipedia.org/wiki/Apache_Subversion) -->
<!-- [![Mercurial](assets/mercurial.jpeg)](https://en.wikipedia.org/wiki/Mercurial) -->

<a href="https://en.wikipedia.org/wiki/Git"><img src="assets/git.png" style="max-width: 100px; padding-right: 10px;" /></a>
<a href="https://en.wikipedia.org/wiki/Apache_Subversion"><img src="assets/svn.png" style="max-width: 100px; padding-right: 10px;" /></a>
<a href="https://en.wikipedia.org/wiki/Mercurial"><img src="assets/mercurial.jpeg" style="max-width: 100px; padding-right: 10px;" /></a>

Follow the links to learn more about the different version control options.

For our Soul Encoded tutorials, we will be focusing on Git.

## The Problem And Solution
Here is a simple example of a problem that Git solves for software engineers.

Steps
1. A engineer writes and saves the code.
2. A engineer changes the code and saves over his previous changes
3. A engineer realizes that he actually needs the changes that he saved over.

If we did not have version control for this example we would not have access to the code that we saved over.
So the first problem that Git solves for us is providing a **history**

With Git, we can go back to the previous point we committed in our history.

Another big problem that Git solves is dealing with collaborations between many engineers. Imagine for a moment if you and I started writing a essay together, and we are both working on the same section of the essay. Eventually we would need to **merge** our work together in a smart and precise way. Git solves this problem for us.

## Essentials

In this section we will go over the bare essentials you need to work on the Git Soul Encoded challenge.

### Terminologies and Concepts

When working with git there are a few terminologies and concepts that you need to understand

- **Staging**: For all changes that are made they will be either un-staged or staged. This means, that they are either ready to be committed or not yet ready to be committed
- **Committed**: This is essentially saving the staged changes, but it also creates a node
- **Nodes**: a node is a unique point in time in our git history.  

a general work flow would be as follows:

Steps:
1. A engineer writes and saves codes.
2. A engineer adds the saved changes to the staging area.
3. A engineer will commit those changes and thus creating a node in our history, this also clears the staging area.

<img src="assets/stage.png" style="width: 250px;"/>

- **Branching**: The best way I can describe branching is with a multiverse example. Imagine a timeline where someone starts a alternate universe. Branching is essentially creating a new timeline in our git history.

- **Merging**: Merging is used to merge two branches back into one branch. One note is that when you initialize git into your project, you create a default **master** branch.


<img src="assets/git-nodes.png" style="width: 450px;"/>

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

Note some git commands has flags e.g. `git commit -m "commit message here"` the `-m` stands for message and the `"commit message here"` is the string that will be saved as a message. You will need to figure out the flags and parameters to complete the below challenges.

HINT: `git add`, `git checkout`, and `git merge` will need flags or parameters to use.

## Github vs Git
So a lot of new engineers get confused by Git vs Github. We will go over Github in the next sections, but basically Github is a web based version control service that hosts your projects in a online repository.

In simple terms, Github can save your project online in a repository, then you can use Git to make changes to your repository.

Most importantly, Github uses Git. Github has a few additional commands that you will need to learn in the next section.

## Challenge

Prerequisites for this challenge
- [IDE](https://github.com/SoulEncoded/IDE)
- [Command Line]()

NOTE: if this is your first time using git you need to set your git config.

`git config --global user.name "John Doe"`
`git config --global user.email johndoe@example.com`

In this challenge do the following:

1. Create a new project in your workspace and initialize git control
2. Create a new javascript file and add `console.log('hello');` to the first line
3. Commit these changes
4. Create and Checkout a new branch
5. Reopen the javascript file and change the code on the same line to `console.log('new branch');`
6. Merge this new branch back into your master
7. Resolve your merge conflicts and make one final commit with the changes from the merge.

With these steps you have gone through a major work flow using git.

For solutions go to the top and check out the solutions branches
![solutions](assets/solutions.png)

## Additional Resources
- [Git Official Docs](https://git-scm.com/doc)
- [Derek Banas Git tutorials](https://www.youtube.com/watch?v=r63f51ce84A)
