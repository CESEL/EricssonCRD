FILE=proposal

default: $(FILE).pdf

$(FILE).pdf: $(FILE).tex 

	pdflatex $(FILE)
	bibtex $(FILE)
	pdflatex $(FILE)
	pdflatex $(FILE)

move:
	mv *.cb *.cb2 *.bbl *.blg *.brf *.lof *.lol *.lot *.out *.toc *.log *.aux *.pdf tmp/

	
