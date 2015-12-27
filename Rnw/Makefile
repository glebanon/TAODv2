data: data.Rnw
	~/Library/R/3.2/library/knitr/bin/knit computing_data.Rnw

python: python.Rnw
	~/Library/R/3.2/library/knitr/bin/knit computing_python.Rnw

tools: tools.Rnw
	~/Library/R/3.2/library/knitr/bin/knit computing_tools.Rnw

all: *.Rnw
	~/Library/R/3.2/library/knitr/bin/knit computing.Rnw
	
clean:
	rm -f computing*.{ps,pdf,log,aux,out,dvi,bbl,blg}