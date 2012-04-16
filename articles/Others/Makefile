# Makefile for the unicode UTF8 html files
# Author: Tuan T. Pham
# Last updated: 03/14/12

# Lists of html files to be generated in groups of five

LIST0=NBR_US_India.html NYT_020811.html COB_ChokePoint.html COB_ChokePoint_Solar.html JTO_020711.html
LIST1=LE_020711.html JTO_020611.html TN_HumanRights.html FP_012711.html FP_1210.html
LIST2=OCA.html STRATFOR_GeoChina.html
# STRATFOR_RDK_1848.html 

OUTPUT=$(LIST0) $(LIST1) $(LIST2)

all: $(OUTPUT)

################################################################################
# LIST0=NBR_US_India.html NYT_020811.html COB_ChokePoint.html COB_ChokePoint_Solar.html JTO_020711.html

NBR_US_India.html: NBR_US_India.txt
	htmlizer.pl -t="Một bước tiến trong hợp tác quốc phòng Hoa Kỳ -- Ấn Độ" NBR_US_India.txt

COB_ChokePoint_Solar.html: COB_ChokePoint_Solar.txt
	htmlizer.pl -t="Gió và Mặt Trời" COB_ChokePoint_Solar.txt

COB_ChokePoint.html: COB_ChokePoint.txt
	htmlizer.pl -t="Nút cổ chai: Trung Quốc" COB_ChokePoint.txt

NYT_020811.html: NYT_020811.txt
	htmlizer.pl -t="Tất cả chúng ta là người Ai Cập" NYT_020811.txt

JTO_020711.html: JTO_020711.txt
	htmlizer.pl -t="Năm 1989 của thế giới Ả Rập" JTO_020711.txt

################################################################################
# LIST1=LE_020711.html JTO_020611.html TN_HumanRights.html FP_012711.html FP_012711.html

# translated by Diên Vỹ, x-cafevn.org
JTO_020611.html: JTO_020611.txt
	htmlizer.pl -t="Khủng hoảng lương thực đang đe dọa Châu Á" JTO_020611.txt

# translated by Dalat036, x-cafevn.org
LE_020711.html: LE_020711.txt
	htmlizer.pl -t="Những cuộc cách mạng tại thế giới Ả Rập" LE_020711.txt

FP_012711.html: FP_012711.txt
	htmlizer.pl -t="Cuộc chạy đua phát minh vĩ đại - Adam Segal" FP_012711.txt

# Cymbidium, x-cafevn.org, chuyển ngữ
# Diên Vỹ hiệu đính
TN_HumanRights.html: TN_HumanRights.txt
	htmlizer.pl -t="Nhân Quyền Trong Lịch Sử - Samuel Moyn" TN_HumanRights.txt 

FP_1210.html: FP_1210.txt
	htmlizer.pl -t='Hồi Kết của sự ""Trỗi Dậy Hòa Bình"? Elizabeth Economy' FP_1210.txt

################################################################################
# LIST2=OCA.html STRATFOR_RDK_1848.html STRATFOR_GeoChina.html
OCA.html: OCA.txt
	htmlizer.pl -t="Hãy chiếm giữ Đại Lộ Trường An" -a="Wu Yun -- Alec Ash translated" OCA.txt

STRATFOR_GeoChina.html: STRATFOR_GeoChina.txt
	htmlizer.pl -t="Địa chính trị của Trung Quốc" STRATFOR_GeoChina.txt

STRATFOR_RDK_1848.html: STRATFOR_RDK_1848.txt
	htmlizer.pl -t="1848: Dự báo của lịch sử đối với Trung Đông" -a="Robert D. Kaplan" STRATFOR_RDK_1848.txt

clean:
	rm -fr *.html
