open: lineare-algebra.pdf
	open lineare-algebra.pdf

%.pdf: %.ps
	ps2pdf $<

%.ps: %.dvi
	dvips -o $@ $<

lineare-algebra.dvi: lineare-algebra.tex einfuehrung.tex formeln.tex mengen.tex \
                     beweise.tex gruppen.tex ringe.tex komplexe-zahlen.tex \
                     zahlentheorie.tex vektorraeume.tex determinanten.tex \
                     lineare-gleichungen.tex rekurrenz-gleichungen.tex
	latex lineare-algebra.tex

