"Humean Supervenience Debugged" Presentation
============================================

Overview
--------

This is a repo I use for assorted presentations.

Quick Start
-----------

To compile the presentation with pandoc, run the following command:

    pandoc -t beamer -V theme:CambridgeUS Presentation.md -o Slides.pdf -s --slide-level=3 --template=beamer.tex --latex-engine=xelatex --toc

To compile the handout with pandoc, run the following command:

    pandoc -o Handout.pdf Presentation.md --template=template.tex

To compile the outline with pandoc, run the following command:

    pandoc -o Outline.pdf Outline.md --template=template.tex 

Design Goals
------------

-   Use the same Markdown file for presentation and handout
-   Use beamer for presentation, LaTeX for handout
-   Make presentation beautiful

To do
-----

Generalize the beautiful presentation edits for use elsewhere.
