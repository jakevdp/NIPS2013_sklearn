sklearn-nips-mloss.pdf: sklearn-nips-mloss.bib sklearn-nips-mloss.tex
	pdflatex -shell-escape sklearn-nips-mloss.tex
	bibtex sklearn-nips-mloss
	pdflatex -shell-escape sklearn-nips-mloss.tex
	pdflatex -shell-escape sklearn-nips-mloss.tex

partial:
	pdflatex -shell-escape sklearn-nips-mloss.tex

clean:
	rm -f *.log *.out *.aux *.bbl *.blg sklearn-nips-mloss.pdf
