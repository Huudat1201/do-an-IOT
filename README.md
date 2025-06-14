🤖 Đồ án Hệ thống nhúng: Xe dò line và tránh vật cản
📌 Giới thiệu
Đây là đồ án môn Hệ thống nhúng được thực hiện tại Trường Đại học Sư Phạm Kỹ Thuật TP.HCM. Dự án xây dựng một mô hình xe tự hành, có khả năng:
- Dò theo vạch line màu đen trên nền trắng.
- Phát hiện và tránh vật cản bằng cảm biến hồng ngoại.
- Ứng dụng: mô phỏng hệ thống vận chuyển thuốc trong bệnh viện, chuyển thuốc từ quầy đến các phòng bệnh theo tuyến đường cố định, tự động né vật cản trên đường đi.
🎯 Mục tiêu
- Xe chạy theo line với độ chính xác cao.
- Vận tốc ổn định.
- Có khả năng nhận biết và tránh vật cản.
🧰 Phần cứng sử dụng
Thiết bị
- Arduino Uno R3:	Vi điều khiển chính (ATmega328P), 14 chân I/O số.
- Module L298: Mạch cầu H điều khiển động cơ, hỗ trợ điều khiển 2 động cơ DC.
- Cảm biến hồng ngoại:	Phát hiện line và vật cản.
- Động cơ giảm tốc + bánh xe:	Cung cấp lực và di chuyển.
- Mạch hạ áp:	Cung cấp nguồn điện ổn định cho hệ thống.
- Dây nối (đực - cái): Kết nối các linh kiện trên breadboard.
💻 Phần mềm:
- Arduino IDE (lập trình, nạp code)
- Ngôn ngữ: C/C++
👨‍💻 Nhóm thực hiện:
- Hồ Đức Pháp – 20110691
- Lê Hoàng Hải Đăng – 20110123
- Nguyễn Hữu Đạt – 20110631
