LATEX := pdflatex
DRAFT := $(LATEX) -draftmode

all: mlsquick.pdf montex.pdf zanabazr.pdf

MLSQUICK := '\date{November 1st, 2001}\input{mlsquick.tex}'

mlsquick.pdf: mlsquick.tex
	$(DRAFT) $(MLSQUICK)
	$(DRAFT) $(MLSQUICK)
	$(LATEX) $(MLSQUICK)

MONTEX := montex.tex

montex.pdf: montex.tex
	$(DRAFT) $(MONTEX)
	$(DRAFT) $(MONTEX)
	$(LATEX) $(MONTEX)

ZANABAZR := zanabazr.tex

zanabazr.pdf: zanabazr.tex
	$(DRAFT) $(ZANABAZR)
	$(DRAFT) $(ZANABAZR)
	$(LATEX) $(ZANABAZR)
