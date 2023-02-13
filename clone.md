# The `git clone` command

Although humans can't quite clone yet, *git* sure can, and a great tool it is. Following are a few of its capabilities:

Git's `clone` command has *one* function at its core: clone a repository into a new directory. However, there are many flavours to this tool.

It can create remote-tracking branches for each branch in a cloned repository, and creates and checks out an initial branch that is forked from the cloned repository's currently active branch, given some configuration.

## Syntax
```bash
$ git clone https://github.com/user_name/repo.git
```
or when using SSH authentication

```bash
$ git clone git@github.com:user_name/repo.git
```

## Some options for this command are:

`-l`, `--local`

`-s`, `--shared`

`-q`, `--quiet`

`-v`, `--verbose`

`--progress`

`-n`, `--no-checkout`

and many more!