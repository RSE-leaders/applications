defaults: wsspe3.pdf

%.pdf: %.md rse.bib Makefile
	pandoc $< --filter pandoc-citeproc --csl=ieee.csl --bibliography=rse.bib -o $@

clean:
	rm -f *.pdf
