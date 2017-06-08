all: PID_effective_control_flow_recovery.pdf

PID_effective_control_flow_recovery.pdf: pid.pdf
	mv $< $@

%.pdf: %.tex
	latexrun $<

.PHONY: clean

clean:
	rm -rf latex.out
