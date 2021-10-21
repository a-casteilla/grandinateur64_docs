LATEX = pdflatex
DOCSRC = overview.tex instruction_set.tex opcodes.tex fdl-1.3.tex
DOCPDF = ${DOCSRC:.tex=.pdf}

all: ${DOCPDF}
	
overview.pdf:
	${LATEX} overview.tex

instruction_set.pdf:
	${LATEX} instruction_set.tex
	${LATEX} instruction_set.tex

opcodes.pdf:
	${LATEX} opcodes.tex
	${LATEX} opcodes.tex

fdl-1.3.pdf:
	${LATEX} fdl-1.3.tex

clean:
	rm -f *.aux *.log *.bak *.pdf *.toc

