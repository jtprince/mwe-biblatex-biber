This is [a minimum working example of using biblatex and
biber](http://tex.stackexchange.com/questions/21486/error-message-when-using-biber).  

Note that I needed to install the following packages on top of my fairly minimal texlive install:

    tlmgr install csquotes biblatex logreq

Then, compile with:

    latexmk -xelatex doc.tex

And (mostly) clean up with:

    latexmk -xelatex -C doc.tex
