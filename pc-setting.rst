My computer
============

I use Linux. I don't want to use proprietary softwares if possible.

Hardware
---------

Any Intel (or AMD) x86 based computer is OK, though I like
laptops. Currently I use the Lenovo Thinkpad X200 with Japanese
keyboard with US-keymap. The Japanese keyboard is nice because it has
more keys than US-keyboard.

Memory size is important. I need at least 2 GB for working comfortably.

OS
---

I use Ubuntu linux 9.10. On the every Ubuntu release, I prefer to re-install
the ubuntu linux, which is enough easy. Up-grading is sometimes
troublesome.

Softwares
----------

As far as it is possible, I use the softwares that can be installed
through the package manager of the Linux distribution I use. So
usually it is limited to the open source softwares. But some
exceptions still exist.

GNOME-terminal
^^^^^^^^^^^^^^^

Now I like the Liberation Mono font.

Zsh
^^^^

I spend most my time with terminal emulator. Zsh helps to reduce a lot
of typing due to the special features, especially the strong
completion, and I like the number expansion::

   % echo {001..010}
   001 002 003 004 005 006 007 008 009 010

Vim
^^^^

Vim is my default text editor.

Emacs (23.1.1 gtk)
^^^^^^^^^^^^^^^^^^^

I use Emacs for programing, writing code documents and scientific
manuscripts. I use 'Liberation Mono' font with the full screen mode.

IPython & `Numpy <http://numpy.scipy.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

I often use the combination of IPython & Numpy as an ad-hoc matrix calculater.

LaTeX
^^^^^^

For writing manuscripts. On Emacs, I use `YaTeX <http://www.yatex.org/>`_.

`Sphinx <http://sphinx.pocoo.org/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Writing code documents and small reports.

Illustrator
^^^^^^^^^^^^

I use Adobe Illustrator on Windows on VMware. Large amount of physical
memory makes comfortable operation of Illustrator significantly.


Virtual machines
-----------------

Virtual machines are significantly useful. The virtual machine images
are saved in a portable HDD formatted in ext3. I bring this HDD
between the office and my home.

Windows XP
^^^^^^^^^^^

Windows XP is enough small and simple with respect to the current
hardware, even if it is installed on VMware on Linux.

Ubuntu server
^^^^^^^^^^^^^^

I use the Ubuntu server to store data used privately. 

Most of the data are kept under Subversion, the version-control
system. This helps a lot to keep the files fresh among the computers I
use (at office, at home, at the other office...)

I store a lot of papers to be read for the research on Wiki. I use
Hiki because it is simple. The essential functions are the file
attachment and the text search.

Internet service
-----------------

Without internet, I can not work any more.

Gmail
^^^^^^

I often changed my positions to work for. E-mail addresses tied to
those are not convenient.

DropBox
^^^^^^^^

This is useful to pass large files that are not accepted by some mail
servers, because sometimes I generate and have to send huge data and
animations to co-workers.

SourceForge
^^^^^^^^^^^^

To organize open source projects, this service is extremely useful.

Keymap
-------

I use US keymap with Japanese keyboard on X200 modified by ``.xmodmap``::

   remove Lock = Caps_Lock
   remove Control = Control_L
   keysym Control_L = Caps_Lock
   keysym Caps_Lock = Control_L
   add Control = Control_L
   add Lock = Caps_Lock
   
   keycode 97 = grave asciitilde
   keycode 49 = Escape asciitilde






.. |sflogo| image:: http://sflogo.sourceforge.net/sflogo.php?group_id=161614&type=1
            :target: http://sourceforge.net

|sflogo|
