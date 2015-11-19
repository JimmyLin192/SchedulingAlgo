name=main

all: 
	pdflatex main.tex

bib:
	bibtex main

push:
	git add ${name}.pdf ${name}.tex ${name}.bib Figures/* makefile
	git commit -m "push everything"
	git push

clean:
	${name}.aux ${name}.log
