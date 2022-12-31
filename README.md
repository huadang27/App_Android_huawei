#Android
 
I.	TỔNG QUAN VỀ ĐỀ TÀI:
1.	Giới thiệu đề tài:
Ngày nay, xu hướng phát triển công nghiêp hóa – hiện đại hóa đất nước ngày càng được đẩy mạnh. Để có thể đáp ứng được khối công việc ngày càng gia tăng , đòi hỏi con người phải có phương pháp quản lý hợp lý giúp tiết kiệm thời gian và chi phí cũng như công sức lao động.
Thấy những khó khăn, hạn chế trong việc quản lý nhân viên, việc xây dựng một ứng dụng quản lý giúp người quản trị dễ dàng hơn trong việc quản lý nhân viên một cách nhanh chóng, truy xuất dữ liệu nhanh hơn là điều vô cùng cần thiết.
Qua nghiên cứu, học hỏi thầy cô và bạn bè về giải pháp quản lý nhân viên. Em xin đưa ra giải pháp “Phần mềm Quản lý nhân viên trên thiết bị di động”. Hy vọng phần mềm này có thể giúp người quản lý theo dõi, tổ chức tốt các nhân viên của mình. Và việc có thể cài đặt trên các thiết bị di động giúp việc quản lý thuận tiện hơn.
2.	Mục tiêu đề tài:
Giúp người quản lý cài đặt ứng dụng quản lý nhân viên trên các thiết bị di động, quản lý thuận tiện, có thể theo dõi các nhân viên mọi lúc, đạt các mục tiêu:
	- Quản lý các tài khoản đăng nhập.
- Quản lý thông tin của nhân viên .
3.	Yêu cầu:
- Tính tiện dụng: Ứng dụng đơn giản, dễ sử dụng. Thiết kế mới, nhưng không cầu kì gây khó chịu cho người dùng.
- Tính đúng đắn: Ứng dụng chạy không lỗi.
- Tính thích nghi: Ứng dụng tương thích với nhiều loại thiết bị di động với cấu hình phần cứng cũng như thiết kế kiến trúc khác nhau.
- Tính tiến hóa: Ứng dụng dễ dàng cho việc phát triển thêm các tính năng mà không gây ảnh hưởng đến các tính năng đã phát triển trước.
4.	Thư viện sử dụng:
- implementation 'com.huawei.agconnect:agconnect-core:1.5.2.300'
- implementation 'com.huawei.hms:hwid:5.3.0.302'
- implementation "com.huawei.agconnect:agconnect-auth:1.5.2.300"
- implementation 'com.huawei.hms:scan:1.3.2.300'
- implementation 'com.huawei.agconnect:agconnect-cloud-database:1.4.8.300'
- implementation platform('com.google.firebase:firebase-bom:28.3.0')
- implementation 'com.google.firebase:firebase-analytics:19.0.0'
- implementation 'com.google.firebase:firebase-database:20.0.0'
- implementation 'com.google.android.material:material:1.2.0'

I.	THIẾT KẾ
1.	Màn hình đăng nhập

 ![image](https://user-images.githubusercontent.com/78135100/210136838-87cad075-fea5-4122-a3ce-5e14a663ad6f.png)
 
2.	Màn hình chính Admin

  ![image](https://user-images.githubusercontent.com/78135100/210136841-59704527-aeba-477b-a869-e3e0ede97da3.png)
  
3.	Màn hình chính User

 ![image](https://user-images.githubusercontent.com/78135100/210136843-b879d99c-ce4d-47a2-bc36-3c6ff78e800f.png)
4.	Màn hình tạo tài khoản 
 
![image](https://user-images.githubusercontent.com/78135100/210136847-2cd7006c-62c9-4dc8-ae3a-5f26dd6c9334.png)
![image](https://user-images.githubusercontent.com/78135100/210136849-f3ba4475-41ae-489e-9ee7-0e10204f15b2.png)
![image](https://user-images.githubusercontent.com/78135100/210136855-876bf968-c738-4b69-a6a4-13e8a3679350.png)
![image](https://user-images.githubusercontent.com/78135100/210136860-c99e5a1f-b91e-4c20-8b0e-937e0fd77e96.png)

5.	Màn hình Scan QR Code

 ![image](https://user-images.githubusercontent.com/78135100/210136864-80950feb-f45b-4dbf-a215-4670b02603e6.png)
 
6.	Màn hình danh sách nhân viên

  ![image](https://user-images.githubusercontent.com/78135100/210136866-b07f6aff-5182-4117-bf7c-ac719ca57580.png)
  
7.	Màn hình Gen QR Code

 ![image](https://user-images.githubusercontent.com/78135100/210136869-bf7258b0-13ab-4ebe-9953-73ae4bd572df.png) 
 
8.	Màn hình Pay Roll

 ![image](https://user-images.githubusercontent.com/78135100/210136871-bbc8af07-855b-458e-b461-a464e94926a0.png)
 
9.	 Màn hình quên mật khẩu
 
 ![image](https://user-images.githubusercontent.com/78135100/210136875-5a2255a9-c5d8-4bc2-a9ed-c6bc5942b6de.png)


Tải app tại : https://appgallery.huawei.com/app/C104586707



https://user-images.githubusercontent.com/78135100/210137882-96625671-00fa-4a26-bdb6-b72490e94013.mp4



III.	TỔNG KẾT
1.	Kết luận
Ngày nay, quy mô các công ty ngày càng mở rộng và phát triển, nên rất khó khăn cho việc quản lý. Chúng ta không thể áp dụng hình thức quản lý truyền thống (giấy tờ, sổ sách,…) cho một thời đại 4.0 như hiện nay. Vì vậy, phần mềm “Phần mềm Quản lý nhân viên trên thiết bị di động” ra đời giúp khắc phục những nhược điểm và khó khăn của việc quản lý truyền thống, tạo sự thuận tiện có thể theo dõi chỉ bằng thiết bị thông minh nhỏ gọn.

2.	Hướng phát triển
Có thể phát triển:
- Nâng cấp, bổ sung thêm nhiều tính năng mới.
- Bảo mật chặt chẽ hơn.
- Cải tiến giao diện chuyên nghiệp hơn.
- …
 

