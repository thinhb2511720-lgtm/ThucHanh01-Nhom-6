Nhiệm vụ 2:
Giải quyết Sự cố Kỹ thuật Đơn giản với AI

Nhiệm vụ 2.1: Sử dụng AI tìm cách khắc phục sự cố Wi-Fi mất kết nối trên Windows 10.
I.Mục tiêu:
Trình bày quy trình chẩn đoán và xử lý lỗi máy tính không thể kết nối mạng Wi-Fi trên môi trường Windows 10.
II.Nội dung thực hiện
1.Sử dụng AI để tìm kiếm phương pháp
Các đề xuất từ AI gồm 
-Cài lại Driver Wi-Fi (Xử lý khi Driver bị lỗi/treo).
-Dùng công cụ sửa lỗi tự động (Network Troubleshooter).
-Reset toàn bộ IP và DNS (Bằng CMD).
2.Áp dụng các phương pháp
Áp dụng AI để tìm kiếm phương pháp
-Bước 1: Nhấn chuột phải vào nút Start, chọn Device Manager.
-Bước 2: Mở mục Network adapters, tìm dòng có chữ Wireless hoặc Wi-Fi.
-Bước 3: Chuột phải vào dòng đó chọn Uninstall device (Lưu ý: Không tích vào ô "Delete the driver software").
-Bước 4: Trên menu, chọn Action > Scan for hardware changes để Windows tự động cài lại driver mới.
 Dùng công cụ sửa lỗi tự động (Network Troubleshooter)
-Bước 1: Vào Settings > Update & Security > Troubleshoot.
-Bước 2: Chọn Additional troubleshooters > Internet Connections.
-Bước 3: Nhấn Run the troubleshooter và làm theo hướng dẫn trên màn hình.
Reset toàn bộ IP và DNS (Bằng CMD)
-Bước 1: Mở Start, gõ cmd, chọn Run as administrator.
-Bước 2: Gõ lần lượt 3 lệnh quan trọng sau (nhấn Enter sau mỗi dòng):
netsh winsock reset
ipconfig /release
ipconfig /renew
3. Đánh giá và kết luận

Phương pháp
Hiệu quả
Ưu điểm
Nhược điểm
1. Cài lại Driver
Cao (80%)
Giải quyết triệt để lỗi mất biểu tượng Wi-Fi hoặc driver bị "treo". Không cần kết nối mạng để thực hiện.
Yêu cầu người dùng phải xác định đúng tên thiết bị mạng trong danh sách phần cứng.
2. Troubleshooter
Trung bình
Thân thiện, dễ sử dụng, tự động hóa hoàn toàn. An toàn cho người dùng không chuyên.
Thường chỉ sửa được các lỗi bề mặt, ít hiệu quả với các lỗi hệ thống phức tạp.
3. Reset CMD
Rất cao (90%)
Xử lý triệt để các lỗi liên quan đến xung đột IP, DNS, hoặc lỗi giao thức mạng. "Làm sạch" hoàn toàn kết nối.
Yêu cầu sử dụng dòng lệnh chính xác. Bắt buộc phải khởi động lại máy.



Kết luận chung: Để tối ưu hóa quy trình sửa lỗi, người thực hiện nên áp dụng theo trình tự: Phương pháp 1 (Kiểm tra Driver) trước tiên để loại trừ lỗi phần cứng/giao tiếp. Nếu driver ổn định nhưng vẫn không có mạng, áp dụng Phương pháp 3 (Reset CMD) để xử lý các vấn đề về giao thức mạng. Phương pháp 2 nên được dùng như bước kiểm tra nhanh ban đầu cho người dùng phổ thông.

