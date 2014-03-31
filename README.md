slink
=====

This is a script to create symbolic links based on the contents of file named `links` in whatever you current directory is. I mainly created this to aid in deploying git managed projects without having to move files out of the repo.

Deploy:
-------

**Prerequisites:**

 * A POSIX shell
 * ~/bin in your path

**Procedure:**

The deployment assumes you will have ~/bin in your PATH.

Clone repo to your home directory:

    git clone git://github.com/nurfherder/slink.git ~/code/bin/slink

Install into ~/bin:

    cd ~/code/bin/slink
    ./slink
