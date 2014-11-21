
all:
	pdflatex proposal.tex
	bibtex proposal.aux
	pdflatex proposal.tex
	pdflatex proposal.tex
	pdflatex proposal.tex
	mv *.aux build/.
	mv *.log build/.
	mv *.bbl build/.
	mv *.blg build/.
	mv *.out build/.
	mv proposal.pdf Nordstrom_SocialWiFi.pdf

clean:
	rm -fv *.aux *.pdf *.log *.bbl *.blg *.out
