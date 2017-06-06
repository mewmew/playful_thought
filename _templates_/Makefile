all: pid.pdf

%.pdf: %.tex
	latexrun $<

.PHONY: clean

clean:
	rm -rf latex.out
