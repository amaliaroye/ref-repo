# Git

#### Create
Clone an existing repository to local directory
`$ git clone ssh://user@domain.com/repo.git`

Create a new local repository in current working directory
`$ git init`

#### Local Changes
View changed files in working directory
`$ git status`

Add all current changes to the next commit
`$git add .`

Add changes made to `<file>`
`$ git add <file>`

Commit staged changes with message
`git commit -m '<message>'`


# Git and Github

### Create
`$ git clone <url>` Clone an existing repository
`$ git init` Create a new local repository in current directory

### local
`$ git status` View changed files in working directory
`$ git add .` Add all current changes to next commit
`$ git commit -m 'Commit message'` Commit local changes with commit message
`$ git --amend` Change the last commit


### branches
`$ git branch <new-branch>` Create new branch based on current HEAD
`$ git checkout <branch>` Switch HEAD branch



#### Local Changes
`git init`: create a new local repository in current directory
`git status`: View changed files in current working directory
`git add <file>`: Add current changes to the next commit
`git commit -m "<message>"`: Commit staged
`git log`: Show all commits
`git clone <url>`: Clone an existing repository

#### Branches
`git branch`: List branches
`git branch <new-branch>`
`git checkout <branch>`: Switch HEAD branch
`git checkout -b <branch-name>`: Creates new branch and checks it out
`git merge <branch>`: Creates a commit with two unique parents
`git rebase <branch>`:
`git checkout <HEAD>^`: Checkout parent commit (relative to current HEAD)
`git checkout HEAD~<number>`: Switches head to a specific number of commits back
`git branch -f main HEAD~3`: Force moves the main branch to three parents behind HEAD

`git reset <HEAD>`: reverts a branch to an older commit (ok for local branches)
`git revert <HEAD>`: reverses changes on remote branches and shares the changes with others

#### Github
`git remote add <shortname> <url>`: Add new remote repository
`git push origin main`: Push changes onto remote repository


# Git Commit Messages
[How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/#imperative)

### 7 Rules of Commit messages
1. Separate subject from body with a blank line
2. Limit the subject line to 50 characters
3. Capitalize the subject line
4. Do not end the subject line with a period
5. Use the imperative mood in the subject line
6. Wrap the body at 72 characters
7. Use the body to explain what and why vs. how

#### Example
```
Summarize changes in around 50 characters or less

More detailed explanatory text, if necessary. Wrap it to about 72
characters or so. In some contexts, the first line is treated as the
subject of the commit and the rest of the text as the body. The
blank line separating the summary from the body is critical (unless
you omit the body entirely); various tools like `log`, `shortlog`
and `rebase` can get confused if you run the two together.

Explain the problem that this commit is solving. Focus on why you
are making this change as opposed to how (the code explains that).
Are there side effects or other unintuitive consequences of this
change? Here's the place to explain them.

Further paragraphs come after blank lines.

 - Bullet points are okay, too

 - Typically a hyphen or asterisk is used for the bullet, preceded
   by a single space, with blank lines in between, but conventions
   vary here

If you use an issue tracker, put references to them at the bottom,
like this:

Resolves: #123
See also: #456, #789
```
