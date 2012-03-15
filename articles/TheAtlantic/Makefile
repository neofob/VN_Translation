# Makefile for the unicode UTF8 html files
# Author: Tuan T. Pham
# Last updated: 02/14/12

# Lists of html files to be generated in groups of five

LIST0=ElegantDecline.html NextEmpire.html NgoaiGiao.html XuanVan.html

OUTPUT=$(LIST0)

all: $(OUTPUT)

################################################################################
# LIST0 =XuanVan.html OW.html OCA.html US_India.html AmericasEdge.html

XuanVan.html: XuanVan.txt
	htmlizer.pl -t="Nhớ nhà: Tại sao người di trú Trung Quốc sẽ làm 3.2 Tỷ chuyến đi trong 40 ngày"\
-a="Helen Gao" XuanVan.txt

NgoaiGiao.html: NgoaiGiao.txt
	htmlizer.pl -a="Goldberg and Kaplan" -t="100 ngày đầu tiên - Ngoại Giao" NgoaiGiao.txt

NextEmpire.html: NextEmpire.txt
	htmlizer.pl -a="Howard W. French" -t="Đế Chế Kế Tiếp?" NextEmpire.txt

ElegantDecline.html: ElegantDecline.txt
	htmlizer.pl -a="Robert D. Kaplan" -t="Sự Suy Thoái Tao Nhã" ElegantDecline.txt

clean:
	rm -fr *.html
