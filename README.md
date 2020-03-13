TABLE OF CONTENTS
=================

1 Introduction

2 Download

3 Installation

4 Additional Packages

5 Package Compatibility

6 Author/Maintainer

7 Bug Reports

8 Known Problems


1 INTRODUCTION
==============

A frame that counts words by document, section and subsection in LaTeX
using TeXcount and Overleaf. The counts are colour-coded and made in the right-hand 
margin with the marginnote package.

This material is published under the LPPL 1.3c: This work may be
distributed and/or modified under the conditions of the LaTeX Project
Public License, either version 1.3c of this license or (at your option) any
later version. This version of this license is in
https://www.latex-project.org/lppl/lppl-1-3c.txt
and the latest version of this license is in
https://www.latex-project.org/lppl.txt
and version 1.3c or later is part of all distributions of LaTeX version
2005/12/01 or later.


2 DOWNLOAD
==========

`focusframe' is available from github: https://github.com/billyblacklington/focusframe

The repository contains the files:

  the manual (focusframe.pdf),

  the compiled example (focusframe.tex),

  the style file (focusframe.sty),

  and this README


3 INSTALLATION
==============

Using Overleaf: Copy focusframe.sty to your repository.


4 ADDITIONAL PACKAGES
=====================

This style package loads other packages:

* etoolbox, https://ctan.org/pkg/etoolbox

* fancybox, https://ctan.org/pkg/fancybox

* marginnote, https://ctan.org/pkg/marginnote

* xcolor, https://ctan.org/pkg/xcolor

* xfp, https://ctan.org/pkg/xfp


5 PACKAGE COMPATIBILITY
=======================

There are no known compatibility issues with other packages.


6 AUTHOR/MAINTAINER
===================

Billy Black


7 BUG REPORTS
=============

A bug report should contain:

* Comprehensive problem description. This includes error or
  warning messages.

* \errorcontextlines=\maxdimen can be added in the
  TeX code to get more information in TeX error messages.

* Minimal test file that shows the problem, but does not
  contain any unnecessary packages and code.

* Used drivers/programs.

* Version information about used packages and programs.

* If you are using LaTeX, then add "\listfiles". Then
  a list of version information is printed at the end
  of the LaTeX run.

* Please no other files than the minimal test file.
  The other files .log, .dvi, .ps, .pdf are seldom
  necessary, so send them only on request.

* Please .zip or .tar.gz your file(s) before sending them

Bug address
-----------

Bug reports can be send to the maintainer:

Billy Black

<william [dot] black [at] hdr [dot] mq [dot] edu [dot] au>


8 KNOWN PROBLEMS
================

* Counting subsubsections is not supported by TeXcount and therefore is not a feature of focusframe.

* Identical subsection or section names will lead to errors.

* Symbols in subsection or section names may lead to errors.

* Does not count words that are created by another function; for example, will not count wordscreated by \lipsum or \bibliography.
