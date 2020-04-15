# Toolbox

A bunch of scripts cobbled together into an organized repo. It's inevitable that I'll forget what some of these are for, or how to install them when I migrate to another machine, so this will serve as a documentation of sorts.

Scripts that I've copied from other people online are excluded from this public repo for obvious reasons.

## Environment

```
GNU bash, version 5.0.16(1)-release (x86_64-pc-linux-gnu)
Linux 5.6.3-arch1-1
```

## Setup

Add these two lines to `.bashrc`:

```sh
export TOOLBOX=/path/to/toolbox
source $TOOLBOX/uh-completion.bash
```
Drop a symlink to [`util/uh`](https://github.com/dkim286/toolbox/tree/master/util#uh) inside `/usr/local/bin` or any other convenient location pointed by `$PATH`.

Symlink other scripts as you see fit. 

## Usage

To see a list of categories, run:

```text
$ uh
```

To see a list of scripts belonging to a category, run:

```text
$ uh CATEGORY
```
