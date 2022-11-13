# latex_cv

## prerequistes 
see: 
* https://help.ubuntu.com/community/LaTeX
* https://ctan.org/pkg/xcolor

    
    /usr/share/texlive/texmf-dist/tex/latex/

    unzip xkeyval.zip
    cd xkeyval 
    xelatex xkeyval.ins
    mv xkeyval ~/texmf/tex/latex/
    texhash ~/texmf


## build new stuff
    cd ./cv
    xelatex cv_rr_en.tex

    xelatex motivation-letter_rr_en.tex

## build old stuff
    xelatex cv_2021_sample.tex

    xelatex motivation-letter_rr_de.tex

## build bibliography

1. bibtex josephine_template
2. xelatex josephine_template.tex

## latex on windows systems
https://www.latexbuch.de/latex-windows-installieren/#x1-110003.1

* download: http://www.tug.org/texlive/
* fonts: tug.org/fonts/getnonfreefonts/install-getnonfreefonts.

### bibtex
https://tex.stackexchange.com/questions/342608/where-can-i-get-a-windows-version-of-bibtex-exe
