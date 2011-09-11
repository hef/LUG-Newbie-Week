Newbie Week Slides
==================

This is a collection of presentations used by the Univerity of Illinois Linux User's group for the (bi)annual Newbie's Week.  The event is designed to introduce users to linux concepts at UIC.


The Presentations
=================

 - [Working with code](https://acm.cs.uic.edu/jenkins/job/Newbie%20Week%20Presentations/ws/code.pdf)
 - [Installing Ubuntu](https://acm.cs.uic.edu/jenkins/job/Newbie%20Week%20Presentations/ws/install_ubuntu.pdf)
 - [Using Linux at UIC](https://acm.cs.uic.edu/jenkins/job/Newbie%20Week%20Presentations/ws/linux_uic.pdf)
 - [Remote Access](https://acm.cs.uic.edu/jenkins/job/Newbie%20Week%20Presentations/ws/remote_access.pdf)
 - [The Shell](https://acm.cs.uic.edu/jenkins/job/Newbie%20Week%20Presentations/ws/shell.pdf)

Building the Presnetations
====================================

The presentations are built with scons and latex/beamer.

1. install latex with beamer for your platform:
2. run `scons`

Arch
----

    sudo pacman -Sy scons texlive-most
    yaourt -Sy latex-beamer
