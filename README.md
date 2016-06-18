# git-rpr

A custom git command to review a pull request

## install

Put the script somewhere on your `$PATH`, like `~/bin`, make it executable and that's it.

## dependency

It depends on [git-bp](https://github.com/robertbasic/git-branching-point)

## git config

Set the following global git configs:

```
git config --global diff.tool vimdiff
git config --global merge.tool vimdiff
git config --global difftool.prompt vimdiff
```

## usage

```
git checkout branch-from-which-a-pr-is-created
git rpr
```
foo
