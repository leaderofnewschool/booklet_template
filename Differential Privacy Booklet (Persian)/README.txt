Hi!

Welcome to DP Booklet project:)

Just pay attention to some notes please;

1. For writing any new chapter, please create a new folder with chpter name add your ".tex" and any other plot, etc. you have.

---------------------------------------------------------------------

2. After writing your content, add a "\include{*name_of_chapter*/*name_of_chapter} 
to the right place (after line 205 in "Report.tex")

---------------------------------------------------------------------

3. PLEASE DO NOT CHANGE ANYTHING ELSE IN "Report.tex".

---------------------------------------------------------------------

4. In this template, we don't use "ref.bib" for citations. In refrence folder, there is a .tex file with the same name. We itemize articles we want to cite. So don't put "Bibtex" files in refrence, just write the content (such as name of authors, year, journal, etc.) as a plain text after your \bibitem. 

    *preferred format: Name1, Name2, \textit{"Title of paper"}, name of confrence or journal, vol. and pages (if any), doi: (if available)
    (An example is cited for better undrestanding.)

---------------------------------------------------------------------

5. For each new chapter start writing in .tex file by:
    \chapter{name1}
    ...
    \section{name2}
    ...
    \subsection{name3}
    ...

---------------------------------------------------------------------

6. Write your latin\English sentence in:
    \lr{...}
Or for paragraphs or long text:
    \begin{latin}
    ...
    \end{latin}

---------------------------------------------------------------------

7. To have a more beautiful table of contetns, please use * for subsubsection{}




Best wishes and good luck!