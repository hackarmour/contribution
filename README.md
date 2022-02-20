# Contribution Guidelines

These are the guidelines to be followed if you want to contribute to our projects. There might be special ones for each, so please refer to the readme of the particular project.

-   Always before contributing, use the Issue Tracker to check about what you can improve in the project. You can also use it to file bugs and self assign it if you can fix them!
-   Lint your project for potential bugs using the recommended linter before pushing the code. Guidelines could be found in the respective readme.
-   Make sure the commit message is in present tense and helps to understand what feature is implemented and which section has been edited.

## Committing

Please follow the following prefix rule for all commits:

-   `feat` – a new feature is introduced with the changes
-   `fix` – a bug fix has occurred
-   `chore` – changes that do not relate to a fix or feature and don't modify src or test files (for example updating dependencies)
-   `refactor` – code formatting & refactoring such as white-space, missing semi-colons and so on.
-   `docs` – updates to documentation such as a the README or other markdown files
-   `test` – including new or correcting previous tests
-   `optimize` – optimization and performance improvements
-   `ci` – continuous integration related
-   `build` – changes that affect the build system or external dependencies
-   `revert` – reverts a previous commit
-   `<feat>` mentioning the specific part of the code such as a subdirectory changed

## Pull Requests

**Create a Fork.**

You can fork a GitHub repository by just going to the GitHub repository URL, and clicking on the **Fork** Button

![some alt](https://raw.githubusercontent.com/hackarmour/discord-assistant/main/docs/Pasted%20image%2020210523153059.png)

**Then, clone the forked repo by**

```
git clone https://github.com/{userName}/{forkedRepo}.git
```

**Create a new working branch**

Right after cloning the repo, switch to a new branch because we dont want to mess with the main/master branch, you do this by

```
git checkout -b {newBranchName}
```

The branch name can be anything, just it shouldn't get conflicted with other branch names, such as, when you create a branch `testing` and the branch already exists on the main upstream, it will create conflicts. 

After switching branches,

**Commit the changes**

after cloning and going into your project, make your changes like creating new files, editing files or deleting files, and after you are done,

to commit the changes, first, add all the edited or new files by

```
git add .
```

and then commit it with a comment by,

```
git commit -m "some message here"
```
and by this you have commited your changes, only thing left is pushing those changes
![some alt](https://raw.githubusercontent.com/hackarmour/discord-assistant/main/docs/Pasted%20image%2020210523154447.png)

**Pushing the changes**

After we are done commiting, we need to push it to the forked repo, we will do this by,

```
git push -u origin {branchName}
```
![some alt](https://raw.githubusercontent.com/hackarmour/discord-assistant/main/docs/Pasted%20image%2020210523154537.png)

Note: `origin` here refers to the remote repo, and it may be different, please check your remote repo using command,

```
git remote
```

default is `origin`

**Creating a PR**

Finally, after all things done, we have to just create a pull request to the remote upstream, we do this by going to the forked repo, and github will automatically reminds us that our repo is *n* commits ahead the main branch of remote upstream,

![some alt](https://raw.githubusercontent.com/hackarmour/discord-assistant/main/docs/Pasted%20image%2020210523154628.png)

We will just click on the *compare & pull request* button to start creating a PR.
it will show something like this

![some alt](https://raw.githubusercontent.com/hackarmour/discord-assistant/main/docs/Pasted%20image%2020210523154733.png)

We will now add a title and a description about what we changed to created.
after it, we will just click on the *create pull request*.

## Code of Conduct

We have attaches the Code of Conduct for most of the public projects and repositories. Make sure you read them before doing any contribution. We have also attached some templates related to issues and pull requests so make sure you are following them too. 😃
