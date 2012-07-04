druid.pdf: druid.tex druid.sagetex.out
	pdflatex druid.tex
druid.sagetex.out: druid.sagetex.sage
	sage druid.sagetex.sage
druid.sagetex.sage: druid.tex
	latex druid.tex

clean:
	rm *.pdf *.aux *.dvi *sagetex* *.log
