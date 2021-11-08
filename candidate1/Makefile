PDF = Coding-interview-1

all:	clean ${PDF}

${PDF}:	main.tex
	latexmk -pdf -jobname=$@ main

clean		:
		rm -f *.aux *.bbl *.blg *.dvi *.log *.ps *.fdb_latexmk *.fls *.bib *-1.pdf *-2.pdf *.bst *.pdf
