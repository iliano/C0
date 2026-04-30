This repository consists primarily of the Wiki (see link above) for the C0 
tutorial. It also contains some code used in the tutorial itself.

Tools for generating the wiki
=============================

We can build the wiki with the same tools that GitHub uses, more or less. 
Everything is either written in Python or Ruby, both of which have build 
systems with mostly reasonable defaults.

Git Repository
--------------
You need to have a git repository checkout of the wiki (wherever you see
`C0-Tutorial` below, it's referring to the git repository directory). 

To get a read-only copy, you can do this (NOTE: don't do the optional Gollum
install below if you check out a read-only copy):

    $ git clone git://github.com/iliano/c0.wiki.git

If you want to enter your password a lot, you can do this:

    $ git clone https://iliano@github.com/iliano/c0.wiki.git

If you give GitHub your public key, you can do this:

    $ git clone git@github.com:iliano/c0.wiki.git

As long as you never edit files in this directory directly (only by using a
separate repository and/or the GitHub web interface), you only need to know
two git commands.

Pull from GitHub:

    $ git pull --rebase

Push to GitHub:

    $ git push
