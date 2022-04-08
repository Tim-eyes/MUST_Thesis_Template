Before you edit your paper in this Latex file, you should pay attention to
the following items:

1. recommend to use xelate to compile the thesis.tex, other compile like pdflatex may have traditonal Chinese font problem 
2. re-write your info like according to defining command, including name, student-No and so on.  
3. If you choose minted page to code listing, you need to compile tex file like this (flag -shell-escape):
    $ latex -shell-escape input
The same holds for other processors, such as xelatex. In fact you can give up this package by using package `listings` with command `\lstset{...}`. 
4. For the reference in bibliography, you should copy the details of your paper from 
Google Scholar to bibliography/bibliography.bib. (ps. the default bibtex format is  apalike in this template); it also can support the requirement -- automatically omit author name, if necessary.
5. The Thesis fonts are respectively `Times New Roman` for English and `宋体繁`(songti) for traditional Chinese using package `xeCJK` or `CJK`.
6. The template using `report` as document class and `chapter` as primary heading.
7. If you want to add new macros packages, be careful of the options to individual packages with same dependencies or in same re-implementation.
8. Being appreciated to any feedback and suggestion from students and professor.  