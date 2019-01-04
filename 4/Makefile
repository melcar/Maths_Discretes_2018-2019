all: Solutions.tex
	pdflatex -synctex=1 -interaction=nonstopmode Solutions.tex
	pdflatex -synctex=1 -interaction=nonstopmode Solutions.tex

release: all _release_ clean

_release_:
	mv Solutions.pdf SolutionsTP4.pdf

clean:
	rm -f Solutions.aux Solutions.log Solutions.synctex.gz Solutions.toc Solutions.tex.bak Solutions.out Solutions.bbl Solutions.bcf Solutions.blg Solutions.run.xml

purge: clean
	rm -f Solutions.pdf
