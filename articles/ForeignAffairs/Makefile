# Makefile for Foreign Affairs articles
# Author: Tuan T. Pham
# Last updated: 02/26/12

# Lists of html files to be generated in groups of five

LIST0=FA_0109.html FA_0111.html

OUTPUT=$(LIST0)

all: $(OUTPUT)

################################################################################
# LIST0 =FA_0109.html FA_0111.html

FA_0109.html: FA_0109.txt
	htmlizer.pl -a="Anna-Marie Slaughter" -t="Lợi thế Hoa Kỳ" FA_0109.txt

FA_0111.html: FA_0111.txt
	htmlizer.pl -t="Sức Mạnh Chính Trị của Truyền Thông Xã Hội -- Clay Shirky" FA_0111.txt

clean:
	rm -fr *.html
