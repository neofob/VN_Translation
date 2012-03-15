# Makefile for Economist articles
# Author: Tuan T. Pham
# Last updated: 02/26/12

# Lists of html files to be generated in groups of five

LIST0=Econ_081910.html

OUTPUT=$(LIST0)

all: $(OUTPUT)

################################################################################
# LIST0 = Econ_081910.html

Econ_081910.html: Econ_081910.txt
	htmlizer.pl -t="Trung Quốc và Ấn Độ - Cuộc tranh tài của thế kỷ" Econ_081910.txt

clean:
	rm -fr *.html
