# Toolbox

A bunch of scripts cobbled together into an organized repo. 
Scripts that I've copied from other people online are excluded from this public repo for obvious reasons.

## Environment

```console
$ bash --version
GNU bash, version 5.1.16(1)-release (x86_64-pc-linux-gnu)
Copyright (C) 2020 Free Software Foundation, Inc.
License GPLv3+: GNU GPL version 3 or later <http://gnu.org/licenses/gpl.html>

This is free software; you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.
```

```console
$ uname -a
Linux cork 5.16.5-arch1-1 #1 SMP PREEMPT Tue, 01 Feb 2022 21:42:50 +0000 x86_64 GNU/Linux
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
