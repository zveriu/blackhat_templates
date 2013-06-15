# name of the tex file, without extension
FILENAME=bh13us_slides

all: rub $(FILENAME).tex beamerthemebh13us.sty

rub:
	rubber --pdf $(FILENAME).tex

view:
	evince $(FILENAME).pdf &

clean:
	rubber --clean bh13us_slides.tex
	rm -f $(FILENAME).pdf
	rm -f *.dvi *.ps *.aux *.log *.bbl *.blg *~ *.out *.dia~ *.bak *.nlo
	rm -f figures/*~
	rm -f images/*combined-eps-converted-to.pdf


