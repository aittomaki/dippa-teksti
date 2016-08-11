#!/bin/bash
pdflatex dippa
bibtex dippa
pdflatex dippa
pdflatex dippa
DATE=`date +%y%m%d`
cp dippa.pdf compiled/dippa-$DATE.pdf
