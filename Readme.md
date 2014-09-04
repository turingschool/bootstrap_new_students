Dotfiles
========

Dotfiles are files that configure the applications you use.
They are named this because they typically begin with a dot,
which makes them hidden by default in unix.

Prerequeisites
--------------

You will need to have Git installed and know how to navigate the file system.
If you don't have these, remind me to go find them and come update these instructions.

Installation
------------

First clone this repo somewhere (it doesn't matter where, but probably put it someplace that won't annoy you).

```sh
$ git clone https://github.com/turingschool/bootstrap_new_students.git
```

Then cd into this repo, all commands below will be run from here.

```sh
$ cd bootstrap_new_students
```

Install [pryrc](https://github.com/turingschool/bootstrap_new_students/blob/master/pryrc) to configure [pry](http://pryrepl.org/) to work with [Atom](http://atom.io/).

```sh
$ cp pryrc ~/.pryrc
```

Install [bash_profile](https://github.com/turingschool/bootstrap_new_students/blob/master/bash_profile) to configure [bash](https://en.wikipedia.org/wiki/Bash_%28Unix_shell%29), this:

```sh
$ cp bash_profile ~/.bash_profile
```

Install [gitconfig](https://github.com/turingschool/bootstrap_new_students/blob/master/gitconfig) to configure [git](http://git-scm.com/),
then edit the information under `[user]` to match your information.

```sh
$ cp gitconfig ~/.gitconfig
```
