
all: nfsv4.pdf
.PHONY: all

nfsv4.pdf: nfsv4.dot

%.pdf : %.dot
	dot -Tpdf $< -o $@

