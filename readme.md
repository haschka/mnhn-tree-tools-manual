# Reading the Manual

* Open or download
  https://gitlab.in2p3.fr/mnhn-tools/mnhn-tree-tools-manual/-/blob/master/manual.pdf

# Building the Manual from Latex Source
 
clone the repository and perform

```
xelatex masterfile
bibtex masterfile
xelatex masterfile
xelatex masterfile

pdfunite title-page-sans-nom.pdf masterfile.pdf manual.pdf
```
