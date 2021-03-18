.PHONY: clean

NAME = article

%.pdf:	%.tex
	pdflatex -pdf $<

$(NAME).pdf: $(DIRS)

clean:
	latexmk -C
