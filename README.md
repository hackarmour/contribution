# Contribution
We accept contributions from everyone regardless of any differences. Help us in our mission to make the decentralized infosec search engine for everyone, and make our community the best. You can always ask queries in the `#contributors-general` on our [discord server](https://discord.gg/ePAVq2frFB)

## Finding something to work on

You can always look at our repositories' issue tracker to find bugs you can potentially fix. If you want to work on a new feature or have some ideas about our products, you can let us know about it through our discord server. Here are few projects you can contribute to:

- If you know HTML/CSS/JS
  - The front-end of hackarmour search engine [React js] will be open to everyone soon to take a look at and also, file issues and PRs.
  - Some major components of the backend [nodejs] will also be open to all soon
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
-   Follow the repo's branching system. The branching system we use is discussed below.
-   Lint your project for potential bugs using the recommended linter before pushing the code. Guidelines could be found in the respective readme.
-   Make sure the commit message is in present tense and helps to understand what feature is implemented and which section has been edited.

## Steps to follow
- Fork the repo from github.
- Clone the forked repo from your account to your local machine using `git clone <url>`.
- Swith the branch you may want to work on, using `git checkout <branch-name>` or create your own feature branch using `git branch <new-branch>`.
- Run `git add .` and `git commit -m "<your message>"` to commit your changes. See [committing](#committing) for recommended commit messages.
- Push your code to your forked repo using `git push origin <new-branch>`.
- Go to your fork on github, and make a pull request. You can request reviews from the staff as well.
- Refer [here](https://www.freecodecamp.org/news/how-to-make-your-first-pull-request-on-github-3/) for detailed docs [Also includes syncing your fork from the upstream].

## Branching System

We encourage the use of [GitHub Flow](https://githubflow.github.io/) branching system to manage our branches. It states the main branch should always be stable and deployable, and feature branch needs to be created to add new stuff, and all experiments shall be done there.

### Committing

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

### Code of Conduct

We have attaches the Code of Conduct for most of the public projects and repositories. Make sure you read them before doing any contribution. We have also attached some templates related to issues and pull requests so make sure you are following them too.
