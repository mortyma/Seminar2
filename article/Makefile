.PHONY: clean

NAME = article

%.pdf:	%.tex
	pdflatex $<

$(NAME).pdf: $(DIRS)

clean:
	latexmk -C
