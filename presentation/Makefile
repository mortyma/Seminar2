.PHONY: clean

NAME = presentation

%.pdf:	%.tex
	pdflatex $<

$(NAME).pdf: $(DIRS)

clean:
	latexmk -C
