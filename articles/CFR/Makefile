# Makefile for CFR articles
# Author: Tuan T. Pham
# Last updated: 02/26/12

# Lists of html files to be generated in groups of five

LIST0=CFR_021611.html CFR_121511.html CFR_090210.html CFR_JWebb.html

OUTPUT=$(LIST0)

all: $(OUTPUT)

################################################################################
# LIST0 =CFR_121511.html CFR_021611.html CFR_090210.html CFR_JWebb.html

CFR_121511.html: CFR_121511.txt
	htmlizer.pl -t="Chiếm giữ Ô Khảm" -a="Elizabeth C. Economy" CFR_121511.txt

CFR_021611.html: CFR_021611.txt
	htmlizer.pl -t="Kinh tế và khủng hoảng nước ở Trung Quốc -- Một cái nhìn mới" CFR_021611.txt

CFR_090210.html: CFR_090210.txt
	htmlizer.pl -t="Tránh một cơn bão ở Biển Đông - Joshua Kurlantzick" CFR_090210.txt

CFR_JWebb.html: CFR_JWebb.txt
	htmlizer.pl -t="Trò chuyện với Thượng Nghị Sĩ Jimm Webb" JWebb.txt

clean:
	rm -fr *.html
