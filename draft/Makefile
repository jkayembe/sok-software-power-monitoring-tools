
all: main.pdf

main.pdf: main.tex bib/main-zotero.bib bib/temp-manual.bib
	latexmk -pdf main.tex

clean:
	latexmk -c -pdf main.tex

distclean:
	latexmk -C -pdf main.tex
	rm -f main.bbl

