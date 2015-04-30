# prerequirements

* pandoc
* texlive-latex-base
* texlive-latex-recommended
* texlive-latex-extra
* texlive-fonts-recommended [solves error: I can't find file `ecrm1095']
* texlive-lang-german [solves error: Package babel Error: Unknown option `ngerman']
* lmodern [solves error: LaTeX Error: File `lmodern.sty' not found.]
* texlive-fonts-extra [solves error: LaTeX Error: File `paratype.sty' not found.]

# install requirements on debian:
```
sudo apt-get install pandoc texlive-latex-base texlive-latex-recommended texlive-latex-extra texlive-fonts-recommended texlive-lang-german lmodern texlive-fonts-extra
```

# compiling
```
pdflatex --shell-escape Statuten_Funkfeuer_Wien.tex
```
