Newbie Week Slides
==================

This is a collection of presentations used by the Univerity of Illinois Linux User's group for the (bi)annual Newbie's Week.  The event is designed to introduce users to linux concepts at UIC.


Building the Presnetations
====================================

The presentations are built with scons and latex/beamer.

1. install latex with beamer for your platform:
2. run `scons`

Arch
----

    sudo pacman -Sy scons texlive-most
    yaourt -Sy latex-beamer

OS X with macports
------------------

    sudo port install scons texlive-latex texlive-latex-recommended
