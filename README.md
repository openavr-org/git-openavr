Another Set of Git Add-on Tools
===============================

This set of Git add-on tools was inspired by the `git-plus` project on GitHub:

    https://github.com/tkrajina/git-plus

I had made a bunch of improvements and enhancements to that project, but they
didn't fit with the desires of that projects maintainer. My fork of that project
can be found here:

    https://github.com/troth/git-plus

Additionally, I really only use the `git-multi` tool from that project and there
are some features of that version of `git-multi` that I did not find very useful.

Hence, the birth of this project.

Installation
------------

Clone this repository and put the path to it in your `PATH` environment.

Alternatively, you can simply create a symlink to the `git-multi` file in your
`$HOME/bin` directory (assuming `$HOME/bin` is already in your `PATH`).

Usage
-----

Get help from `git-multi`:

    $ git multi -h

You can also use `man` to view the docs from the cloned directory:

    $ man ./git-multi.1
