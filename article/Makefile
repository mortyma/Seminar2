.PHONY: clean

NAME = article

%.pdf:	%.tex
	latexmk -pdf $<

$(NAME).pdf: $(DIRS)

clean:
	latexmk -C
