## <u> Git Status commands </u> 


Git status is a command used in the Git version control system to check the status of a Git repository. It helps to view the current changes that have been made in the repository and have not yet been committed to the repository.

### Description
---


The `git status` command shows the status of the repository, including the state of files that have been added, modified, or deleted, and provides information about any changes that have not yet been staged or committed. The command outputs a summary of the repository's current state, including:

- The branch that the repository is currently on
- The status of the working tree, including changes that have been made but not yet staged
- The status of the index, including changes that have been staged but not yet committed

### Options
---

There are some options of the `git status` command that can be used to display additional information or to modify the behavior of the command:

- `-s`
This option provides a more concise and simplified output, showing the status of each file in a single letter format.

- `--ignored`
This option displays information about files that are ignored by Git, such as files specified in a `.gitignore` file.

- `--porcelain`
This option provides a stable, machine-readable output format that can be used by other tools and scripts.

- `-b`
This option displays information about the current branch, including any upstream tracking information.

### Examples 
---

git status -s 

git status 

git status -b 

### Usage
---

The git status command is used to show the current status of the Git repository. It displays information about which files are currently being tracked or untracked, which changes have been made, and which changes are staged and ready to be committed. This information can be useful for understanding the current state of the repository and for deciding which changes to commit.