all: main.tex
	pdflatex main.tex; bibtex main; pdflatex main.tex; pdflatex main.tex; pdflatex main.tex;

clean: *.pdf
	rm -f *.pdf *.bbl *.log *.aux *.blg *.out *.cut
