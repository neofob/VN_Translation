# Makefile for NPR articles
# Last update: 03/14/12
# Tuan T. Pham
LIST0=NPR_062110.html NPR_071810.html NPR_012611.html
SUB_DIRS=GTR

OUTPUT=$(LIST0)

all: $(OUTPUT)
	-for d in $(SUB_DIRS); do (cd $$d; make all); done

################################################################################
#LIST0=NPR_062110.html NPR_071810.html NPR_012611.html
NPR_012611.html: NPR_012611.txt
	htmlizer.pl -a="Deborah Amos" -t="Cách mạng truyền thông xã hội đến Saudi Arabia" NPR_012611.txt

NPR_071810.html: NPR_071810.txt
	htmlizer.pl -a="Louisa Lim" -t="Người Trung Quốc Tìm Đến Tôn Giáo" NPR_071810.txt

NPR_062110.html: NPR_062110.txt
	htmlizer.pl -a="Lonny Shavelson" -t="Có thêm nhiều người Mỹ gốc Á gia nhập quân đội" NPR_062110.txt

clean:
	rm -fr NPR_*.html
	-for d in $(SUB_DIRS); do (cd $$d; make clean); done
