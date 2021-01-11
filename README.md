# Andrey Sobolev PhD Thesis.

To compile PDF in Ubuntu/Debian:


install Latex and extra packages:
```
sudo apt-get install texlive-latex-base texlive-fonts-recommended texlive-fonts-extra texlive-latex-extra biblatex texlive-full
```

clone this repository
```
git clone git@github.com:asobolev/thesis.git
```

compile PDF
```
cd thesis
pdflatex main.tex; biber main; pdflatex main.tex; pdflatex main.tex
```
