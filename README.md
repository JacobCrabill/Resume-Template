# Resume template in LaTeX

This template came from Overleaf (www.overleaf.com)

To use it, either install the full Texlive distribution and compile in Texmaker (or similar) using pdflatex, **or**, upload all of the files to a blank project in Overleaf and let it do the work for you.

# How To Use

The resume is divided into a few files for organizational purposes. The main / top-level file is main.tex; this file then includes all of the other files.  The main banner for your name is in main.tex; everything else that needs to be modified is in the other files.  The layout, style, pacakges, and useful macros are all defined in main.tex as well.

# Short vs. Long Versions

The template includes a variable in main.tex, `longcv`, which when `true` uses all of the sections, and the long version of every entry in the cv.  When `longcv` is empty / undefined, the short version gets compiled, allowing the same source files to hold both a short 1-page resume as well as a long, multi-page CV.
