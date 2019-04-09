# LogSentinel Merkle Trees Usage Documentation

## Compilation instructions for Ubuntu
First, make sure you have the ```texlive-full``` package installed on your machine. If not, simply run:
```
sudo apt update
sudo apt-get install texlive-full
```

To compile the LaTeX file to a PDF document, run the following commands inside the project directory:
```
latex MerkleTrees.tex
bibtex MerkleTrees
latex MerkleTrees.tex
latex MerkleTrees.tex
pdflatex MerkleTrees.tex
```
