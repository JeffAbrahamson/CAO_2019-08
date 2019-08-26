all: talk.pdf

%.pdf : %.tex ../talk-header.tex ../macros.tex
	pdflatex -halt-on-error $<
