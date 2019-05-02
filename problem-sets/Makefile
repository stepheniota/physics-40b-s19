# Makefile for tex files

ALL: P40B_S19_PSet1.pdf P40B_S19_PSet2.pdf P40B_S19_PSet3.pdf P40B_S19_PSet4.pdf

P40B_S19_PSet1.pdf: P40B_S19_PSet1.tex
	pdflatex P40B_S19_PSet1

P40B_S19_PSet2.pdf: P40B_S19_PSet2.tex
	pdflatex P40B_S19_PSet2

P40B_S19_PSet3.pdf: P40B_S19_PSet3.tex
	pdflatex P40B_S19_PSet3

P40B_S19_PSet4.pdf: P40B_S19_PSet4.tex
	pdflatex P40B_S19_PSet4

.PHONY: clean
clean:
	rm *aux *out *log #*fls *latexmk
