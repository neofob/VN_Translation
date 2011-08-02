all: GTR_051210.html GTR_051210_1.html GTR_051310.html

GTR_051310.html: GTR_051310.txt
	htmlizer.pl -a="Philip Reeves" -t="Trên Con Đường Sỏi Đá, Tuổi Trẻ Ấn Độ Tìm Kiếm\
		Một Đời Sống Tốt Đẹp Hơn" GTR_051310.txt
GTR_051210.html: GTR_051210.txt
	htmlizer.pl -a="Philip Reeves" -t="Thách Đố của Con Đường Cái Quan: Bắt Đầu Từ Đâu?" GTR_051210.txt

GTR_051210_1.html: GTR_051210_1.txt
	htmlizer.pl -a="Steve Inskeep" -t="Một Con Đường Cổ Xưa Đến Tương Lai Ở Ấn Độ, Pakistan" GTR_051210_1.txt
clean:
	rm -fr *.html
