FILTERS = --filter=pandoc-numbering --filter=pandoc-crossref
TEMPLATE = --template=./default.latex
PDFENGINE = --pdf-engine pdflatex

all: fourier.pdf fourier_serie1.pdf probas.pdf

fourier.pdf: fourier.md
	pandoc -s -o $@ $< $(FILTERS) $(TEMPLATE) $(PDFENGINE)

fourier_serie1.pdf: fourier_serie1.md
	pandoc -s -o $@ $< $(FILTERS) $(TEMPLATE) $(PDFENGINE)

probas.pdf: probas.md
	pandoc -s -o $@ $< $(FILTERS) $(TEMPLATE) $(PDFENGINE)

# matrix_inverse.pdf: matrix_inverse.md
# 	pandoc -s -o $@ $< $(FILTERS) $(TEMPLATE) $(PDFENGINE)

# matrice_rot.pdf: matrice_rot.md
# 	pandoc -s -o $@ $< $(FILTERS) $(TEMPLATE) $(PDFENGINE)

# matrices.pdf: matrices.md
# 	pandoc -s -o $@ $< $(FILTERS) $(TEMPLATE) $(PDFENGINE)

# fun_lin.pdf: fun_lin.md
# 	pandoc -s -o $@ $< $(FILTERS) $(TEMPLATE) $(PDFENGINE)

# vecteurs.pdf: vecteurs.md
# 	pandoc -s -o $@ $< $(FILTERS) $(TEMPLATE) $(PDFENGINE)

