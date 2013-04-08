.. -*- restructuredtext -*-

latex-moderncv is a repository containing my resume compiled in latex using a very nice modern theme

Credits
=======

Latex is a fantastic typesetting program that a lot of people use these days, especially the math and computer science people in academia. You can find out more about it here: http://www.latex-project.org/

If you are looking for latex resume templates, I would recommend looking at this nice list an anonymous person put together: http://linuxandfriends.com/2009/12/28/latex-resume-templates/

The moderncv theme for my resume is contributed by Xavier Danaux and can be downloaded here: http://tug.ctan.org/tex-archive/macros/latex/contrib/moderncv/

Prerequisites
=============

You will need to have latex installed on your system. If you are using OSX, the easiest way to get up and running is to download MacTex: http://tug.org/mactex/

Installation
============

Install Latex and download the moderncv theme. Place the moderncv theme somewhere Latex can find it. You can just place the folder in the same place as your .tex file as I have::

    /my-resume
        my-resume.tex
        my-resume.pdf
        /moderncv

Compiling the Resume
====================

Simply use the ``pdflatex`` command in your terminal::

    pdflatex my-resume.tex

Notes
=====

You are free to take my .tex file and modify it to create your own resume. Please don't use my resume for anything else without my permission, though! 

Good luck!
