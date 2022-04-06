Before you edit your paper in this Latex file, you should pay attention to
the following items:

1. recommond to use xelate to complie the thesis.tex, other compile like pdflatex may have traditonal Chinese font problem 
2. rewirte your info like according to defining commond  
3. If you choose minted page to code listing, you need to compile tex file like this (flag -shell-escape):
$ latex -shell-escape input
The same holds for other processors, such as pdflatex or xelatex.
4. For the reference in bibliography, you should copy the details of your paper from 
Google Scholar to bibliography/bibliography.bib. 