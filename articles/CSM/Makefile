# Makefile for Christian Science Monitor articles
# Author: Tuan T. Pham
# Last updated: 02/26/12

# Lists of html files to be generated in groups of five

LIST0=CSM_020711.html CSM_083010.html

OUTPUT=$(LIST0)

all: $(OUTPUT)


################################################################################
# LIST0 = CSM_020711.html CSM_083010.html

# translated by Dalat036, x-cafevn.org
CSM_020711.html: CSM_020711.txt
	htmlizer.pl -t="Làn sóng dân chủ" CSM_020711.txt

CSM_083010.html: CSM_083010.txt
	htmlizer.pl -t="Chiến Hạm Trung Quốc cập bến Miến Điện" CSM_083010.txt

clean:
	rm -fr *.html
