# set-theory
# Set Theory: An Open Introduction

![Book Cover](http://builds.openlogicproject.org/courses/set-theory/settheory.png)

_Set Theory: An Open Introduction_ is a brief introduction to the
philosophy of set theory. It is written for students with a little
background in logic, and some high school mathematics. By the end of
this book, students reading it might have a sense of:

- why set theory came about;
- how to reduce large swathes of mathematics to set theory + arithmetic;
- how to embed arithmetic in set theory;
- what the cumulative iterative conception of set amounts to;
- how one might try to justify the axioms of ZFC.

This repository/directory only contains the LaTeX files and
illustrations needed to typeset the textbook _Set Theory_, which in
turn requires the _[Open Logic
Text](http://github.com/OpenLogicProject/OpenLogic/)_.

You can [download the
PDF](http://builds.openlogicproject.org/courses/set-theory/settheory-screen.pdf)
from the [Open Logic builds
site](http://builds.openlogicproject.org/).

To install and compile:

- Download/install the _Open Logic Text_ from
  [GitHub](http://github.com/OpenLogicProject/OpenLogic/), including
  [photos](https://github.com/OpenLogicProject/photos) if you want those.
- Navigate to the subdirectory `courses/`
- Put the content of this repository into a subdirectory of it, say
  `courses/set-theory`.

If you use `git`, this should do it:
```
# git clone https://github.com/OpenLogicProject/OpenLogic.git
# cd OpenLogic/courses
# git clone https://github.com/OpenLogicProject/set-theory.git
# cd ../assets
# git clone https://github.com/OpenLogicProject/photos.git
```
Inside `courses/set-theory`, you can now compile:
```
# pdflatex settheory-screen
```
or just `# make` if you have `latexmk` installed. (You'll also have to
do `bibtex settheory-screen` for the bibliography.)

The file `settheory-screen.tex` produces a color version of the text
with smaller margins for screen reading.

The file loads `settheory.tex`, which contains the actual material. It
in turn includes other files, most of them from the `OpenLogic`
repository. So you won't get a complete book unless you download into
the right subdirectory of and compile from there.

[![Creative Commons License](http://mirrors.creativecommons.org/presskit/buttons/88x31/png/by.png)](http://creativecommons.org/licenses/by/4.0/) 

_[Set Theory](https://github.com/OpenLogicProject/set-theory/)_ by
[Tim Button](http://nottub.com/) is licensed under a [Creative Commons
Attribution 4.0 International
License](http://creativecommons.org/licenses/by/4.0/).
