build: main.tex
	/usr/bin/pdflatex $<

create_resume:
	cp output/main.pdf ./OcanoaiaAndreiaIrina.pdf

clean:
	rm -rf output/*.aux output/*.log output/*.toc output/*.bbl output/*.blg output/*.out output/*.bcf output/*.xml output/*.xmpi 

cleanall: clean
	rm -rf output/*.pdf output/*.ps output/*.dvi

.PHONY: build, clean, cleanall
