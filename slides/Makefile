p.pdf:  p.tex p.bib basics.tex conclude.tex hints.tex intro.tex
	lualatex p
	biber p
	lualatex p
	lualatex p

clean:
	rm -f p.pdf *.aux p.bbl p.bcf p.blg p.log p.run.xml *~
	rm -f p.done p.dvi p.nav p.out p.snm p.toc p.vrb
