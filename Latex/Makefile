LATEX = xelatex
LFLAG = -synctex=1 -interaction=nonstopmode -c-style-errors
OBJECTS = "Article Template".tex "Ctex Template".tex

.PHONY: everything clean realclean

everything: 
	$(LATEX) $(LFLAG) $(OBJECTS)

clean:
	rm *.aux *.dvi *.log *.synctex.gz

realclean: clean
	rm *.pdf
