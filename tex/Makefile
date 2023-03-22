all: wp2 fed cppdf

wp2: wp2.tex
	pdflatex wp2.tex
	pdflatex wp2.tex

fed: mqs.tex
	pdflatex mqs.tex
	pdflatex mqs.tex

clean:
	-rm wp2.aux  wp2.log  wp2.nav  wp2.out  wp2.pdf  wp2.snm  wp2.toc
	-rm mqs.aux  mqs.log  mqs.nav  mqs.out  mqs.pdf  mqs.snm  mqs.toc

cppdf:
	-cp mqs.pdf ../eo-mqs-demo-20230322.pdf
