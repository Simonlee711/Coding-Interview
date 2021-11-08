PDF = Coding-interview-candidate1

all:	clean ${PDF}

${PDF}:	main.tex
	latexmk -pdf -jobname=$@ main

clean		:
		rm -f *.aux *.bbl *.blg *.dvi *.log *.ps *.fdb_latexmk *.fls *.bib *.bst 
