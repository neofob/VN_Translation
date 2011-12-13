# Silly Makefile for the unicode UTF8 html files
# Author: Tuan T. Pham
# Last updated: 08/02/11

# Lists of html files to be generated in groups of five

LIST4=OCA.html US_India.html AmericasEdge.html
LIST3=020811_NYT.html 021611_CFR.html ChokePoint_vn.html ChokePoint_Solar_vn.html JWebb.html
LIST2=1107.html 020711_CSM.html 020711_Tunisia.html 020711_food.html 020711_1989.html
LIST1=HumanRights.html fp_invRace_vn.html NextEmpire_vn.html ngoai_giao.html china_iran.html
LIST0=csm_083010.html econ_081910.html cfr_090210.html fp_120610.html ff_media.html

OUTPUT=$(LIST0) $(LIST1) $(LIST2) $(LIST3) $(LIST4)

all: $(OUTPUT)


################################################################################
# LIST4 = US_India.html AmericasEdge.html

OCA.html: OCA.txt
	htmlizer.pl -t="Hãy chiếm giữ Đại Lộ Trường An" -a="Wu Yun -- Alec Ash translated" OCA.txt

US_India.html: US_India.txt
	htmlizer.pl -t="Một bước tiến trong hợp tác quốc phòng Hoa Kỳ -- Ấn Độ" US_India.txt

AmericasEdge.html: AmericasEdge.txt
	htmlizer.pl -a="Anna-Marie Slaughter" -t="Lợi thế Hoa Kỳ" AmericasEdge.txt

################################################################################
# LIST3 = 020811_NYT.html 021611_CFR.html ChokePoint_vn.html ChokePoint_Solar_vn.html JWebb.html

# unfinished
JWebb.html: JWebb.txt
	htmlizer.pl -t="Trò chuyện với Thượng Nghị Sĩ Jimm Webb" JWebb.txt

# unfinished
ChokePoint_Solar_vn.html: ChokePoint_Solar_vn.txt
	htmlizer.pl -t="Gió và Mặt Trời" ChokePoint_Solar_vn.txt

ChokePoint_vn.html: ChokePoint_vn.txt
	htmlizer.pl -t="Nút cổ chai: Trung Quốc" ChokePoint_vn.txt

021611_CFR.html: 021611_CFR.txt
	htmlizer.pl -t="Kinh tế và khủng hoảng nước ở Trung Quốc -- Một cái nhìn mới" 021611_CFR.txt

020811_NYT.html: 020811_NYT.txt
	htmlizer.pl -t="Tất cả chúng ta là người Ai Cập" 020811_NYT.txt

################################################################################
# LIST2 = 1107.html 020711_CSM.html 020711_Tunisia.html 020711_food.html 020711_1989.html

020711_1989.html: 020711_1989.txt
	htmlizer.pl -t="Năm 1989 của thế giới Ả Rập" 020711_1989.txt

# translated by Diên Vỹ, x-cafevn.org
020711_food.html: 020711_food.txt
	htmlizer.pl -t="Khủng hoảng lương thực đang đe dọa Châu Á" 020711_food.txt

# translated by Dalat036, x-cafevn.org
020711_Tunisia.html: 020711_Tunisia.txt
	htmlizer.pl -t="Những cuộc cách mạng tại thế giới Ả Rập" 020711_Tunisia.txt

# translated by Dalat036, x-cafevn.org
020711_CSM.html: 020711_CSM.txt
	htmlizer.pl -t="Làn sóng dân chủ" 020711_CSM.txt

# unfinished, The Atlantic, 
1107.html: 1107.txt
	htmlizer.pl -a="Robert D. Kaplan" -t="Sự suy thoái tao nhã của Hoa Kỳ" 1107.txt

################################################################################
# LIST1 = HumanRights.html fp_invRace_vn.html NextEmpire_vn.html ngoai_giao.html china_iran.html
china_iran.html: china_iran.txt
	htmlizer.pl -a="Kaplan D. Kaplan" -t="Bài Học Từ Trung Quốc và Iran" china_iran.txt

ngoai_giao.html: ngoai_giao.txt
	htmlizer.pl -a="Goldberg and Kaplan" -t="100 ngày đầu tiên - Ngoại Giao" ngoai_giao.txt

# partially translated by Lê Quốc Tuấn, x-cafevn.org
NextEmpire_vn.html: NextEmpire_vn.txt
	htmlizer.pl -a="Howard W. French" -t="Đế Chế Kế Tiếp?" NextEmpire_vn.txt

fp_invRace_vn.html: fp_invRace_vn.txt
	htmlizer.pl -t="Cuộc chạy đua phát minh vĩ đại - Adam Segal" fp_invRace_vn.txt

# Cymbidium, x-cafevn.org, chuyển ngữ
# Diên Vỹ hiệu đính
HumanRights.html: HumanRights.txt
	htmlizer.pl -t="Nhân Quyền Trong Lịch Sử - Samuel Moyn" HumanRights.txt 

################################################################################
# LIST0 = csm_083010.html econ_081910.html cfr_090210.html fp_120610.html ff_media.html
ff_media.html: ff_media.txt
	htmlizer.pl -t="Sức Mạnh Chính Trị của Truyền Thông Xã Hội -- Clay Shirky" ff_media.txt

fp_120610.html: fp_120610.txt
	htmlizer.pl -t='Hồi Kết của sự ""Trỗi Dậy Hòa Bình"? Elizabeth Economy' fp_120610.txt

cfr_090210.html: cfr_090210.txt
	htmlizer.pl -t="Tránh một cơn bão ở Biển Nam Trung Hoa - Joshua Kurlantzick" cfr_090210.txt

econ_081910.html: econ_081910.txt
	htmlizer.pl -t="Trung Quốc và Ấn Độ - Cuộc tranh tài của thế kỷ" econ_081910.txt

csm_083010.html: csm_083010.txt
	htmlizer.pl -t="Chiến Hạm Trung Quốc cập bến Miến Điện" csm_083010.txt

clean:
	rm -fr *.html
