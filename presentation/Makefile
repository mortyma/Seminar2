.PHONY: clean

NAME = presentation

%.pdf:	%.tex
	latexmk -pdf $<

$(NAME).pdf: $(DIRS)

clean:
	latexmk -C
