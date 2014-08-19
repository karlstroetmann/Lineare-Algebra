loesung: loesung.pdf
	open loesung.pdf

probe-klausur: probe-klausur.pdf
	open probe-klausur.pdf

%.pdf: %.ps
	ps2pdf $<

%.ps: %.dvi
	dvips -o $@ $<

%.dvi: %.tex
	latex $<




