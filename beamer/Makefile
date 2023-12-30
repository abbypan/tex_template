PRJ = main


all: 
	xelatex ${PRJ}
	biber ${PRJ}
	xelatex ${PRJ}

clean:
	/bin/rm -rf *.bcf *.run.xml *.nav *.snm *.toc *.aux $(addsuffix .bbl,${PRJ}) *.blg *.log *~* *.bak *.out $(addsuffix .pdf,${PRJ}) 
