# Contribution
We accept contributions from everyone regardless of any differences. Help us in our mission to make the decentralized infosec search engine for everyone, and make our community the best. You can always ask queries in the `#contributors-general` on our [discord server](https://discord.gg/ePAVq2frFB)

## Finding something to work on

You can always look at our repositories' issue tracker to find bugs you can potentially fix. If you want to work on a new feature or have some ideas about our products, you can let us know about it through our discord server. Here are few projects you can contribute to:

- If you know HTML/CSS/JS
  - The front-end of hackarmour search engine [React js] will be open to everyone soon to take a look at and also, file issues and PRs.
  - Some components of the backend [nodejs] will also be open to all soon
  - You can make web based CTF challenges with the community, which might be featured in our upcoming CTFs as well!
- If you know python
  - You can work on [monoinit](https://github.com/hackarmour/monoinit), a build system to manage our monorepos.
  - You can also work on revtheshell, and other tools we may release under hackarmour.
- If you know C/C++/Rust/Go
  - You can also work in our core team internally to help us build the core of our search engine.
  - You can join our malware team to create awesome reversing and forensic challenges with the community.
  - Make some high performant tools with us.

 Hackarmour is still in it's initial stage and most of the development is still at the starting phase. Your contribution will really mean a lot to us. Here are some guidelines contributors may keep in mind:

-   Always before contributing, use the Issue Tracker to check about what you can improve in the project. You can also use it to file bugs and self assign it if you can fix them!
-   Also, check out if the project has a `dev` or unstable branch. Don't directly work on the main branch as this can lead to catastrophic conflicts.
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

We have attaches the Code of Conduct for most of the public projects and repositories. Make sure you read them before doing any contribution. We have also attached some templates related to issues and pull requests so make sure you are following them too.
