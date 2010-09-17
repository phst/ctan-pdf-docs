all: manuscript.pdf

manuscript.pdf: manuscript.gls manuscript.ind
	pdflatex manuscript.drv
	pdflatex manuscript.drv
	pdflatex manuscript.drv

manuscript.gls: manuscript.glo
	makeindex -s gglo -o manuscript.gls manuscript.glo

manuscript.ind: manuscript.idx
	makeindex -s gind manuscript

manuscript.glo: manuscript.drv
	pdflatex manuscript.drv

manuscript.idx: manuscript.drv
	pdflatex manuscript.drv

manuscript.drv: manuscript.dtx manuscript.ins
	pdflatex manuscript.ins
