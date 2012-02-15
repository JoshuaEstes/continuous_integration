Symfony 1.4
===========

Contained within these walls are the tools that you will need to setup
your symfony1.4 project with jenkins ci.

Installation
============

The contents of this folder should be copied into you sf_root_dir. After
you do this you should have the build.xml file in the save path as the
symfony executable.

You will need to open up build.xml and edit the db properties. That
should be all you need to do =)

Usage
=====

To trigger a build (which will test all your files to make sure that
your project is stable) you will just need to type "ant" and away it
will go.

Update
------

If at any time you need to update the files in the build directory,
all you have to do is run "ant update" and the files will be downloaded
from github to you build directory.
