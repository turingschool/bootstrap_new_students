Purpose
=======

Eventually I'd like this repository to host everything a student
needs to get bootstrapped into a dev environment. For now, it's
just dotfiles, and a links to material in our curriculum that
cover the other parts.

Setup Your Environment
======================

* To get your environment set up, check out
  [This tutorial](http://tutorials.jumpstartlab.com/topics/environment/environment.html).
* For the basics on how to work in the terminal,
  check out [Terminal and Editor](http://tutorials.jumpstartlab.com/academy/workshops/terminal_and_editor.html).

Dotfiles
========

### What are dotfiles?

Dotfiles are files that configure the applications you use.

They are named this because they typically begin with a dot,
in order to make them hidden by default in Unix.

### Okay, but why?

In many applications, you navigate menus and check boxes
in order to convigure them. This has the convenience of a user
interface.

In Unix, applications are run via the command-line,
they rarely have any sort of visual/navigatable user interface.
So instead they store their configuraiton in files.

This is advantageous, it means
[I can store my dotfiles in source control](https://github.com/JoshCheek/dotfiles/),
clone them onto a new computer, and know my configuration is the same,
share them with you, see everything I've done in one place, etc.

### We have set up some simple dotfiles for you

The leading dollar sign in the code samples below
implies the commands to the right are to be
run from a terminal.

First clone this repo somewhere (it doesn't matter where,
but probably put it someplace that won't annoy you).

```sh
$ git clone https://github.com/turingschool/bootstrap_new_students.git
```

Then cd into this repo, all commands below will be run from here.

```sh
$ cd bootstrap_new_students
```

Install [pryrc](https://github.com/turingschool/bootstrap_new_students/blob/master/pryrc)
to configure [pry](http://pryrepl.org/) to work with [Atom](http://atom.io/).

```sh
$ cp pryrc ~/.pryrc
```

Install [bash_profile](https://github.com/turingschool/bootstrap_new_students/blob/master/bash_profile)
to configure [bash](https://en.wikipedia.org/wiki/Bash_%28Unix_shell%29).

```sh
$ cp bash_profile ~/.bash_profile
```

Install [gitconfig](https://github.com/turingschool/bootstrap_new_students/blob/master/gitconfig)
to configure [git](http://git-scm.com/),
then edit the information under `[user]` to match your information.

```sh
$ cp gitconfig ~/.gitconfig
$ atom ~/.gitconfig
```
