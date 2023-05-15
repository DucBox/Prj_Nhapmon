# Prj_Nhapmon


TRƯỜNG ĐẠI HỌC BÁCH KHOA HÀ NỘI
TRƯỜNG ĐIỆN - ĐIỆN TỬ
___________*___________

 

BÁO CÁO
NHẬP MÔN ĐIỆN TỬ VIỄN THÔNG
NGÀNH HỆ THỐNG NHÚNG VÀ IOT

HỆ THỐNG CHUÔNG CẢNH BÁO THÔNG MINH 
SỬ DỤNG CẢM BIẾN HỒNG NGOẠI

Giảng viên:	Nguyễn Đức Minh

Thành viên nhóm:	MSSV:
Ngô Quang Đức	20213697
Bùi Thành Đạt	20213696
Nguyễn Duy Nhật Quang	20213727
Trần Anh Đức	20213700
Nguyễn Đức Minh Vũ	20213739



HÀ NỘI,  08/2022
MỤC LỤC

MỤC LỤC	1
LỜI NÓI ĐẦU	2
CHƯƠNG I: LÊN Ý TƯỞNG
1.	Ý TƯỞNG 	3
1.1.	Đặt vấn đề	3
1.2.	Tiềm năng trên thị trường	4
2.	CHỈ TIÊU KỸ THUẬT	5
1.1.	Chỉ tiêu chức năng	5
1.2.	Chỉ tiêu phi chức năng	7

CHƯƠNG II: THIẾT KẾ SẢN PHẨM
1.	GIẢI PHÁP 	8
2.	CẤU TRÚC DỮ LIỆU 	17
3.	LẬP TRÌNH 	20
4.	SƠ ĐỒ MẠCH 	21

CHƯƠNG III: THỬ NGHIỆM
1.	CHUẨN BỊ DỤNG CỤ	24
2.	THÍ NGHIỆM	25
2.1.	Đo tầm hoạt động của cảm biến	25
2.2.	Đo cường độ âm thanh của chuông	27
3.	KẾT LUẬN	30


LỜI NÓI ĐẦU 

	Trong thời đại công nghệ phát triển ngày nay, Điện Tử Viễn Thông nói chung và IoT nói riêng dần trở thành một lĩnh vực quan trọng trong đời sống. Các công nghệ dần được thiết kế, phát triển nhằm mục đích cải thiện đời sống cho người dân. Và nhóm chúng em trong quá trình học môn “Nhập môn kĩ thuật điện tử viễn thông” đã tìm hiểu và nhận thấy rằng vấn đề an ninh trong đời sống xã hội ngày nay đang trong tình trạng đáng quan ngại. Từ đó, nhóm chúng em đã quyết định lựa chọn sản phẩm “Chuông cảnh báo thông minh dựa trên ứng dụng cảm biến hồng ngoại” làm sản phẩm trong báo cáo lần này. Toàn bộ phần báo cáo sẽ được chia ra làm 3 chương:
-	Chương 1: Lên ý tưởng: Đặt ra vấn đề thông qua bộ các câu hỏi “Wh” và đưa ra chỉ tiêu cho sản phẩm.
-	Chương 2: Thiết kế sản phẩm: Lựa chọn linh kiện, thiết kế mạch và viết chương trình cho hệ thống.
-	Chương 3: Thử nghiệm: Đưa sản phẩm vào thử nghiệm để đưa ra các đánh giá cuối cùng.

 
CHƯƠNG I: LÊN Ý TƯỞNG
1.	Ý TƯỞNG

1.1	Đặt vấn đề:

-	Trong suốt quá trình học môn “Nhập môn kĩ thuật điện tử viễn thông”, nhóm chúng em đã lựa chọn phương pháp tiếp cận vấn đề và lên ý tưởng thông qua việc trả lời chi tiết cho các câu hỏi What – Why – Who – When – Where.
1.1.1	What ?
-	Hiện nay, thực trạng xuất hiện các đối tượng chuyên thực hiện các vụ trộm cắp ở các khu có người dân sinh sống ngày càng tăng nhanh và diễn ra ngày một phổ biến hơn. 
-	Trong năm 2021, tại Việt Nam đã có tới 37,6% các vụ vi phạm trật tự an ninh xã hội đó là trộm cắp.
-	Chỉ tính riêng tại tỉnh Hà Tĩnh, từ đầu năm 2022 đến giữa tháng 4/2022 trên địa bàn toàn tỉnh đã xảy ra 62 vụ đột nhập, 95 đối tượng trộm cắp tài sản, chiếm 32,1% trong số các vụ phạm pháp hình sự trong toàn tỉnh, gây thiệt hại về giá trị lên tới hàng trăm triệu đồng. 
-	Không chỉ thế, tội phạm đang ngày càng trở nên tinh vi hơn với những thủ đoạn vô cùng khôn lường, khó đoán làm người dân trở nên hoang mang hơn.
1.1.2	How: Vậy tầm ảnh hưởng và quan trọng của thiết bị là như thế nào?
-	Với các lý do trên thì thiết bị báo trộm ngày càng trở nên không thể thiếu.
-	Tầm quan trọng của thiết bị báo trộm đang được khẳng định mạnh mẽ trong cuộc sống hiện đại, trong đó xu hướng với các dòng sản phẩm thông minh đang là sự lựa chọn số 1 của người tiêu dùng thông thái.
-	Vậy nên, “Hệ thống cảnh báo tự động sử dụng cảm biến hồng ngoại” với giá cả đa dạng, thiết kế hợp lý, chất lượng vượt trội so với hầu hết các sản phẩm báo trộm khác chính là giải pháp hoàn hảo để mang tới cho bạn và người thân một cuộc sống an toàn, bình yên và hạnh phúc trọn vẹn.
1.1.3 Why: Tại sao cần thiết bị chuông thông minh này trong đời sống?
-	Thiết bị có thể giúp người dùng chủ động hơn trong việc bảo vệ tài sản của mình.
-	Thiết bị chuông chống trộm thông minh còn góp phần tăng cường, đảm bảo an ninh trật tự cho người dân, khu phố, giúp cho cuộc sống người dân trở nên bình yên hơn.
1.1.4 Who: Vậy đối tượng khách hàng là ai?
-	Sản phẩm này được nhóm em thiết kế nhằm hướng tới đối tượng các hộ gia đình có thu nhập ổn định ( mức lương > 5 triệu/tháng ) thường xuyên vắng nhà và có nhu cầu trong việc chủ động quản lý, bảo vệ tài sản cá nhân.
1.1.5	When: Khi nào thì cần thiết bị này?
-	Sản phẩm chuông chống trộm thông minh này sẽ trở nên vô cũng hữu ích khi được sử dụng chủ yếu vào ban đêm hay cũng chính là lúc chất lượng an ninh trật tự bị giảm đi và khi người dùng đang đi ngủ.
-	Bên cạnh đó, thiết bị còn được sử dụng khi người dùng vắng nhà và không có ai trực tiếp bảo vệ, trông coi tài sản của mình.
1.1.6	Where: Vậy thiết bị được sử dụng, lắp đặt ở những khu vực nào?
	Từ những lý do trên, sản phẩm chuông chống trộm thông minh được nhóm em thiết kế nhằm mục đích sử dụng cho những khu thường xuyên xảy ra trộm cắp, các căn hộ nằm trên những khu phố không đảm bảo an ninh trật tự tốt.

	Thông qua việc trả lời được các câu hỏi trên, nhóm chúng em đã xác định được chính xác tầng lớp khách hàng tiềm năng, mục đích sử dụng cho sản phẩm để từ đó tìm ra hướng đi thích hợp cho việc thiết kế và phát triển sản phẩm.

1.2	Tiềm năng thị trường: 
-    Nhu cầu của con người: Cần có những thiết bị giúp người dùng chủ động hơn trong việc bảo quản tài sản khỏi các hành vi đột nhập, trộm cướp. 
-    Giá thành đa dạng, nhiều phân khúc phù hợp với thu nhập và nhu cầu của mọi người tiêu dùng.  
-    Thiết kế nhỏ gọn, có tính thẩm mĩ, bắt mắt, chất lượng cao và dễ dàng trong việc lắp đặt, sử dụng và quản lý 
-    Tính thực tiễn cao, ngoài việc để cảnh báo đột nhập còn có thể làm đồ trang trí, tích hợp thêm với các hệ thống thông minh trong nhà. 








2.	CHỈ TIÊU KĨ THUẬT & RÀNG BUỘC HỆ THỐNG
2.1	Chỉ tiêu chức năng:
2.1.1	Đầu vào :
-	Dạng tín hiệu : bức xạ hồng ngoại 
-	Độ lớn :
o	Bước sóng trong khoảng 940-950nm
o	Tần số 300 GHz – 300 MHz
o	Năng lượng của photon dao động ở khoảng 1.24 meV – 1.7 eV.
-	Đặc điểm: 
o	 Không thể nhìn thấy bằng mắt người.
o	 Có thể phát hiện được thông qua cảm biến hồng ngoại.
o	Cơ thể sống (con người , động vật ,…) luôn phát ra tia hồng ngoại
-	Ý nghĩa thông tin : Tia hồng ngoại phát ra từ những cơ thể sống ( con người , động vật ,….) do đó sự phát hiện tia hồng ngoại cho thấy sự xuất hiện , chuyển động của cơ thể sống
                      
Hình 1.a
2.1.2	Đầu ra :
-	Dạng tín hiệu : tín hiệu âm thanh 
-	Độ lớn : tối đa 110Db.
-	Đặc điểm :
o	 Phạm vi nghe tối đa: 15m (có vật cản) và 30m (không có vật cản)
-	Ý nghĩa thông tin : tín hiệu âm thanh báo hiệu đã ghi nhận được chuyển động trong phạm vi thu phát của bức xạ hồng ngoại 
-	
2.1.3	Mối quan hệ đầu ra – đầu vào :








 
2.2	Chỉ tiêu phi chức năng:
2.2.1	Năng lượng : 
-	Mắt cảm biến :
o	Công suất tiêu thụ : 150mW
o	Sử dụng nguồn điện : 220V/50Hz
-	Chuông cảnh báo : 
o	 Điện áp : 3-24V
o	Dòng điện : nhỏ hơn 12Mv
o	Sử dụng nguồn điện : 220V/50Hz
2.2.2	Ngoại quan cơ khí :
-	Kích thước :
o	Mắt cảm biến : 70x50x20mm
o	Chuông cảnh báo : 32x24x23mm
-	Màu sắc : màu trắng
-	Vật liệu : nhựa ABS
2.2.3	Hiệu năng :
-	Thiết bị phát và thu bức xạ hồng ngoại liên tục 
-	Trả lại kết quả phát hiện chuyển động sau 1s
-	Khi phát hiện chuyển động chuông cảnh báo phát ra âm thanh trong 30s
2.2.4	Tiêu chuẩn cần tuân theo :
-   Tiêu chuẩn EN-50131 cho hệ thống báo động xâm nhập
-   Tiêu chuẩn an toàn CE
2.2.5	Môi trường hoạt động :
-   Hoạt động tốt trong môi trường có nhiệt độ không quá cao (Do khi nhiệt độ môi trường quá cao có thể dẫn đến lỗi, loạn cảm biến hồng ngoại) 
-   Không hoạt động trong các môi trường như lửa, nước, có nhiều vật cản.
2.2.6	Giá & chi phí :
-	Chi phí sản xuất : 300.000VNĐ

 
CHƯƠNG II: THIẾT KẾ SẢN PHẨM
1.	GIẢI PHÁP
1.1 Sơ đồ khối:


Sơ đồ khối thiết kế sản phẩm cảm biến hồng ngoại phát hiện chuyển động 


1.2 Lựa chọn linh kiện:
1.2.1 KHỐI CẢM BIẾN HỒNG NGOẠI 
 a) Các sản phẩm đang có trên thị trường :  
- Nhóm lựa chọn giữa 2 cảm biến hồng ngoại phổ biến trên thị trường: 
+) Cảm biến hồng ngoại PIR HC-SR501 
+ )Cảm biến hồng ngoại PIR HC-SR505
   
           PIR HC-SR501                                PIR HC-SR505

	PIR HC-SR501	PIR HC-SR505

Điện áp hoạt động	5-20 VDC	4.5-20 VDC
Mức tiêu thụ dòng	< 50uA	< 60uA
Mức đầu ra	High 3.3V/ Low 0V	High 3.3V/ Low 0V
Thời gian trễ	0.3s-300s ( có thể điều chỉnh)	8s ± 30%
Góc quét	< 120 độ	< 100 độ
Khoảng cách quét	<= 4m	< 3m
Nhiệt độ hoạt động	-15 độ C – 70 độ C	-15 độ C – 70 độ C
Kích thước	32mm*24mm	10mm*23mm
Giá	20.000 VND	30.000 VND

•	Nhận xét : 
+) Về phạm vi phát hiện : PIR HC-SR501 có góc quét rộng hơn ( 120 độ so với 100 độ) , có độ đo tối đa xa hơn ( 4m so với 3m) 
+) Về giá : PIR HC-SR501 có giá trên thị trường rẻ hơn 
+) Về hiệu năng hoạt động : PIR HC-SR505 tuy có khả năng cảm biến vô cùng nhạy do đó dễ xảy ra các trường hợp báo động giả, từ đó có thể thấy độ chính xác kém hơn so với PIR HC-SR501.
 
	Nhóm quyết định chọn cảm biến hồng ngoại PIR HC-SR501 


b) Chi tiết về khối:

 
PIR HC-SR501
•	Chỉ tiêu chức năng của khối:
+) Đầu vào: Tín hiệu hồng ngoại thu được từ thân thể con người có bước sóng tối đa 940nm.
+) Đầu ra: Tín hiệu kĩ thuật số.

-	 Nguyên lí hoạt động của khối cảm biến: Các nguồn nhiệt (với người và con vật là nguồn thân nhiệt) đều phát ra tia hồng ngoại, qua kính Fresnel, qua kích lọc lấy tia hồng ngoại, nó được cho tiêu tụ trên 2 cảm biến hồng ngoại gắn trong đầu dò, và tạo ra điện áp được khuếch đại với transistor FET. Khi có một vật nóng đi ngang qua, từ 2 cảm biến này sẽ cho xuất hiện 2 tín hiệu và tín hiệu này sẽ được khuếch đại để có biên độ đủ cao và đưa vào mạch so áp để tác động vào một thiết bị điều khiển hay báo động. 

            









Mô tả hoạt động của cảm biến PIR


             



Trường hợp	PIR HC-SR501	Đầu ra
Có người	Nhận được tín hiệu hồng ngoại từ cơ thể người	1
Không có người	Không nhận được tín hiệu hồng ngoại từ cơ thể người	0

•	Chỉ tiêu phi chức năng của khối:
  

+) Điện áp hoạt động : DC  5V – 20V.
+) Mức tiêu thụ dòng: ≤ 50uA.
+) Đầu ra : High 3.3V/ Low 0V.
+) Thời gian trễ: 5 – 300s có thể điều chỉnh từ 0,xx đến hàng chục giây.
+) Góc quét  <  120 độ.
+) Khoảng cách quét: <= 4m.
+) Kích thước ống cảm biến: 23mm (mặc định).
+) Nhiệt độ hoạt động: -15 độ C -  70 độ C.
+) Kích thước:  32mm*24mm.
+) Khối lượng: 6g.

1.2.2 KHỐI XỬ LÝ 
a) Các sản phẩm có trên thị trường
- Trên thị trường có các sản phẩm phổ biến như :
				+) Arduino Uno R3
				+) Arduino Mini
                                    +) Arduino Mega 2560 R3   
 






-	Nhận xét:
+) Arduino Mini có kích thước nhỏ,giá thành rẻ tuy nhiên sẽ gặp vấn đề về IC điều khiển bị gắn bề mặt trên board .
+) Arduino Uno R3 có kích thước lớn hơn ,giá thành đắt hơn Arduino Mini  tuy nhiên  IC sẽ được giữ trong mạch, tức là có thể tháo ra được. Arduino này có 14 chân Digital và 6 chân Analog, tổng cộng 20 chân GPIO là đủ cho các dự án nhỏ và dự án tầm trung.
+) Arduino Mega 2560 R3 có kích thước lớn nhất , giá thành đắt , tổng cộng 30 đầu vào không phù hợp với dự án nhỏ và trung bình .
		Nhóm quyết định chọn bộ kit Arduino Uno R3

b) Chi tiết về khối 

 
Arduino R3

•	Chỉ tiêu chức năng của khối:
+) Đầu vào: Tín hiệu kĩ thuật số từ module cảm biến hồng ngoại.
+) Đầu ra: Tín hiệu điện áp.

-	 Nguyên lí hoạt động: Arduino có khả năng phát hiện giá trị điện áp như một công tắc BẬT / TẮT bằng cách sử dụng chân đầu vào kĩ thuật số. Khi có đối tượng trong khoảng cách phát hiện, đầu ra ở vị trí CAO (5V hoặc 3.3V), tín hiệu đầu ra sẽ ở vị trí THẤP (0V) nếu không có đối tượng trong phạm vi quét.

Trường hợp	Đầu vào	Đầu ra
Có người	1	Vị trí cao ( 5V hoặc 3.3V)
Không có người	0	Vị trí thấp ( 0V)

•	Chỉ tiêu phi chức năng của khối: 
Vi điều khiển	ATmega328 họ 8bit
Điện áp hoạt động	5V DC (chỉ được cấp qua cổng USB)
Tần số hoạt động	16 MHz
Dòng tiêu thụ	khoảng 30mA
Điện áp vào khuyên dung	7-12V DC
Điện áp vào giới hạn	6-20V DC
Số chân Digital I/O	14 (6 chân hardware PWM)
Số chân Analog	6 (độ phân giải 10bit)
Dòng tối đa trên mỗi chân I/O	30 mA
Dòng ra tối đa (5V)	500 mA
Dòng ra tối đa (3.3V)	50 mA
Bộ nhớ flash	32 KB (ATmega328) với 0.5KB dùng bởi bootloader
SRAM	2 KB (ATmega328)
EEPROM	1 KB (ATmega328)


1.2.3	KHỐI CHUÔNG CẢNH BÁO  
a)	Các sản phẩm trên thị trường : 
   
 
        Chuông cảnh báo Piezo Buzzer                   Chuông 3-24 VDC SFM-27
	Chuông cảnh báo Piezo Buzzer	Chuông 3-24 VDC SFM-27

Điện áp hoạt động	3-20 VDC	3-24 VDC
Dòng điện	≤ 12mA	≤ 30mA
Cường độ âm tối đa	 100 dB	110 dB
Nhiệt độ hoạt động	-20 độ C – 70 độ C	-20 độ C – 70 độ C
Giá	14.000 VND	15.000 VND
   
	Nhóm quyết định chọn Chuông cảnh báo SFM-27

-	Ở đây, chúng ta có:
+) Đầu vào: Tín hiệu điện áp từ Arduino R3.
+) Đầu ra: Tín hiệu âm thanh.

-	Nguyên lí hoạt động: Chuông sẽ phát ra âm thanh cảnh báo trong trường hợp có dấu hiệu đột nhập sau khi nhận tín hiệu điện áp từ khối xử lí.

Trường hợp	Đầu vào	Đầu ra
Có người	Tín hiệu điện áp 5V hoặc 3.3V	Chuông kêu
Không có người	Tín hiệu điện áp 0V	Chuông không kêu

-	 Chỉ tiêu phi chức năng của khối:
+) Điện áp hoạt động: 3-24V 
+) Dòng điện: ≤ 30mA 
+) Cường độ âm tối đa: 110db 
+) Nhiệt độ hoạt động: -20-70 độ C 

2.	CẤU TRÚC DỮ LIỆU

2.1	Sơ đồ khối:

 

2.2	Lưu đồ thuật toán:
 


2.3	  Cơ sở dữ liệu:

	Tên	Khoảng giá trị	Ý nghĩa
Biến của tín hiệu vào	inputPin	2	Chọn GPIO2 là tín hiệu vào
Địa chỉ		258	
Biến của tín hiệu ra	pinSpeaker	10	Chọn GPIO10 là tín hiệu ra
Địa chỉ		256	
Biến của cảm biến	val	0 hoặc 1	0 nếu có chuyển động
1 nếu không có chuyển động
Địa chỉ	Read GPIO2	317	

2.4	  Lưu đồ thuật toán với các dữ liệu ở bước 3:

 

3.	LẬP TRÌNH

-	Phần mềm sử dụng: Arduino IDE 1.8.19

 




4.	SƠ ĐỒ MẠCH

-	Tiếp theo, chúng ta sẽ đến với sơ đồ nguyên lí làm việc cùng với sơ đồ liên kết của hệ thống cảnh báo tự động sử dụng cảm biến hồng ngoại mà nhóm chúng em sử dụng.
-	Sơ đồ nguyên lí :







-	Sơ đồ mạch Proteus :
 

-	Sơ đồ liên kết trong thực tế :

 

CHƯƠNG III: THỬ NGHIỆM
Để kiểm tra tính thực tế cũng như kết quả đầu ra của hệ thống chuông cảnh báo thông minh, chúng ta sẽ tiến hành hai thí nghiệm để kiểm tra tầm hoạt động của cảm biến hồng ngoại và đo cường độ âm thanh trong các không gian, điều kiện khác nhau.
1.	CHUẨN BỊ DỤNG CỤ
-	Một chuông Buzzer 3-24V
-	Một bộ Arduino đã được nạp Code của chương trình
-	Một bộ cảm biến hồng ngoại 
-	5 cặp dây nối đực - cái (1 đầu cắm – 1 đầu đút)
-	Nguồn điện
-	Một máy đo tiếng ồn (Noise Meter). Ở đây nhóm sẽ sử dụng máy đo tiếng ồn SL4200 có xuất xứ từ Trung Quốc. Thiết bị đo với dải tần 31.5-8000Hz, chia thành 3 dải đo: 32-70(Db); 60-100(Db); 90-130(Db) phù hợp cho nhiều mục đích sử dụng.
  
Máy đo độ ồn SL-4200		  Chuông cảnh báo VDC SFM-27
  
Bộ Arduino và cáp nối        Bộ cảm biến hồng ngoại PIR

2.	THÍ NGHIỆM 
2.1	Đo tầm hoạt động của cảm biến:
-	Thí nghiệm: Kiểm tra tầm hoạt động của cảm biến hồng ngoại PIR HC-SR501 (tức khoảng cách từ vị trí có thể nhận diện chuyển động cho tới cảm biến).
2.1.1	Chuẩn bị không gian:
-	Để thực hiện được thí nghiệm này, chúng ta cần một không gian thoáng không có các vật cản để đảm bảo thu được kết quả tối ưu và chính xác nhất.
2.1.2	Các bước thí nghiệm:
B1: Chuẩn bị Code từ trước để sẵn sàng nạp vào bộ Arduino thông qua dây cáp. Code sẽ có inputPin = 2 (Là ngõ tín hiệu vào cho cảm biến) và pinSpeaker = 10 (Chân cho chuông khi phát hiện có đột nhập).
B2: Đầu tiên chúng ta sẽ kết nối bộ Arduino với cảm biến hồng ngoại IR bằng cách: Chúng ta sẽ sử dụng 5 cặp dây nối đực – cái để kết nối Arduino với cảm biến. Dây nối từ đầu GND của cảm biến IR sẽ cắm vào ổ GND trên Arduino. Dây nối từ VCC của cảm biến sẽ cắm vào ổ 5V trên Arduino và dây OUT cuối cùng sẽ cắm vào cổng ra 2 trên Arduino.
B3: Kết nối chuông với Arduino. Dây đen (âm) trên còi hú sẽ nối vào ổ GND trên Arduino còn dây đỏ (dương) sẽ nối vào cổng 10 trên Arduino.
B4: Dùng thước hoặc các dụng cụ đo độ dài để đo khoảng cách từ cảm biến đến vị trí muốn kiểm tra sau đó đánh dấu vị trí lại.
B5: Thực hiện di chuyển tại khu vực đã được đánh dấu trước đó. Nếu chuông kêu lên thì tức là cảm biến hồng ngoại đã quét thành công chuyển động của người để chuông phát ra tín hiệu âm thanh cảnh báo.
B6: Đọc và ghi lại kết quả vào bảng (Nếu chuông kêu tức là tại vị trí với khoảng cách đã xác định đó nằm trong phạm vi hoạt động của cảm biến).
 
Bảng khảo sát tầm hoạt động của cảm biến hồng ngoại PIR
(Bảng 1)

2.2	 Đo cường độ âm thanh của chuông:
Thí nghiệm số 1: Đo cường độ âm thanh của chuông cảnh báo trong điều kiện không có vật cản cụ thể với các khoảng cách 0.1m; 1m và 5m
2.2.1	Chuẩn bị không gian:
-	Để thực hiện được thí nghiệm này, chúng ta cần một không gian thoáng không có các vật cản như cửa kính, cửa gỗ, ...
-	Trong thí nghiệm này, nhóm sẽ đo cường độ âm thanh trong phòng ngủ, phòng khách của căn hộ chung cư trong điều kiện không lí tưởng nhất (do ít nhiều đã chịu ảnh hưởng tiếng ồn âm thanh từ phương tiện dưới đường cũng như thời tiết bên ngoài)
2.2.2	Các bước thí nghiệm:
B1: Chuẩn bị Code từ trước để sẵn sàng nạp vào bộ Arduino thông qua dây cáp. Code sẽ có inputPin = 2 (Là ngõ tín hiệu vào cho cảm biến) và pinSpeaker = 10 (Chân cho chuông khi phát hiện có đột nhập).
B2: Đầu tiên chúng ta sẽ kết nối bộ Arduino với cảm biến hồng ngoại IR bằng cách: Chúng ta sẽ sử dụng 5 cặp dây nối đực – cái để kết nối Arduino với cảm biến. Dây nối từ đầu GND của cảm biến IR sẽ cắm vào ổ GND trên Arduino. Dây nối từ VCC của cảm biến sẽ cắm vào ổ 5V trên Arduino và dây OUT cuối cùng sẽ cắm vào cổng ra 2 trên Arduino.
B3: Kết nối chuông với Arduino. Dây đen (âm) trên còi hú sẽ nối vào ổ GND trên Arduino còn dây đỏ (dương) sẽ nối vào cổng 10 trên Arduino.
B4: Dùng thước đo khoảng cách từ vị trí đo đến vị trí chuông cảnh báo. 
B5: Khởi động máy đo độ ồn. Cấp nguồn cho hệ thống để chuông hoạt động. Cầm máy đo tại vị trí đo đã xác định ở bước trên, chuyển sang chế độ MAX để đo cường độ âm thanh lớn nhất mà tại ví trí đó nhận được.
B6: Đo liên tục trong khoảng thời gian 20s. Sau đó đọc kết quả hiện thị trên màn hình và ghi vào bảng.

 
Bảng kết quả đo cường độ âm thanh của chuông cảnh báo
trong không gian không có vật cản
(Bảng 2)





Thí nghiệm số 2: Đo cường độ âm thanh của chuông cảnh báo trong điều kiện có vật cản cụ thể là một lớp cửa gỗ và tường dày 4cm với các khoảng cách 3m và 10m.
2.2.3	Chuẩn bị không gian:
-	Để thực hiện được thí nghiệm này, chúng ta cần hai không gian được ngăn cách nhau qua một lớp cửa, tường dày 4cm. Cụ thể ở đây là giữa 2 phòng trong 1 căn hộ chung cư.
-	Trong thí nghiệm này, nhóm sẽ đo cường độ âm thanh trong phòng ngủ khi có chuông kêu từ bên ngoài với các khoảng cách 3m, 10m trong điều kiện không lí tưởng nhất (do ít nhiều đã chịu ảnh hưởng tiếng ồn âm thanh từ phương tiện dưới đường cũng như thời tiết bên ngoài)
2.2.4	Các bước thí nghiệm:
-	Thực hiện các bước 1-2-3-4-5-6 giống như ở thí nghiệm thứ nhất.
 
Bảng kết quả đo cường độ âm thanh của chuông cảnh báo
trong không gian có vật cản
(Bảng 3)






3.	KẾT LUẬN

3.1	Về phạm vi, khoảng cách hoạt động của cảm biến:
-	Từ kết quả đo được ở Bảng 1, ta thấy phạm vi hoạt động tốt nhất của cảm biến nằm trong khoảng từ 1m - 4m và trong phạm vi khoảng cách này thì hoạt động của cảm biến vô cùng nhạy và có thể nhận diện, phát hiện lập tức đối tượng ngay khi có dấu hiệu chuyển động.
-	 Cảm biến có thể quét được chuyển động của con người khi cách cảm biến xa nhất là 4m. Đây là phạm vi hoạt động khá rộng và thích hợp trong việc sử dụng làm thiết bị cảnh báo chống trộm.

3.2	Về cường độ âm thanh của chuông cảnh báo phát ra: 
-	Các kết quả đo được có thể sai lệch do dụng cụ đo, do môi trường không lí tưởng (ít nhiều bị ảnh hưởng từ tạp âm do xe cộ, thời tiết và tiếng ồn xung quanh) và do sự không đồng nhất trong thác giữa các lần thực hiện thí nghiệm của người thí nghiệm.
-	Từ các thí nghiệm trên, ta có thể thấy cường độ âm thanh lớn nhất mà chuông có thể phát ra là 110Db là ngưỡng không gây nguy hiểm cho tai người nghe.
-	Qua thực tế chứng minh rằng dù bạn đang ở trong phòng ngủ và chuông cảnh báo đặt ở cửa ra vào (khoảng cách 10-12m và có vật cản là lớp cửa gỗ 4cm) thì vẫn hoàn toàn có thể nghe rõ được tiếng chuông cảnh báo có người đột nhập.






![image](https://github.com/DucBox/Prj_Nhapmon/assets/90564316/1065a686-b0d7-4a3c-8063-6bc06189cee2)
