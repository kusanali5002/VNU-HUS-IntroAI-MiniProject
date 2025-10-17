### 🏷️ Tên nhóm
Nhóm 50

### 📝 Tên dự án
AI cảnh báo kẻ địch mạnh theo thời gian thực cho người chơi Genshin Impact.

### 👥 Thành viên nhóm
| 👤 Họ và tên 🧑‍🎓  | 🆔 Mã sinh viên 🧾 | 🐙 Tên GitHub 🔗     |
|------------------|---------------------|---------------------|
|    Hà Mạnh Dũng  |       23001845      |   @kusanali5002     |

### 🗒️ Tóm tắt
Dự án "AI cảnh báo kẻ địch mạnh theo thời gian thực cho người chơi Genshin Impact" hướng tới mục đích xây dựng một hệ thống hỗ trợ người chơi (đặc biệt là người chơi mới chưa có nhiều kinh nghiệm thám hiểm). Thông qua việc ứng dụng thị giác máy tính (Computer Vision) và xử lý ảnh thời gian thực, hệ thống giúp người chơi nhận biết mối nguy hiểm sớm, đặc biệt khi đang thám hiểm hoặc di chuyển trong bản đồ rộng.

### 🎯 Bối cảnh
- Người chơi mới trong Genshin Impact chưa biết nhiều về thế giới trong game, sẽ thường phải quan sát liên tục và thật tập trung để quan sát những mối nguy hiểm trong thế giới mở. Tuy nhiên trong quá trình tìm kiếm nguyên liệu nấu ăn, nâng cấp, mở rương,... hoặc chỉ đơn giản là mải mê ngắm cảnh đẹp sẽ dễ dàng lọt vào tầm ngắm của kẻ địch.
- Dự án giúp người chơi được cảnh báo trước về những kẻ địch mạnh xuất hiện trong khu vực tầm nhìn để có thể có các đối sách phù hợp như dịch chuyển khỏi khu vực hay chuẩn bị thực phẩm để đối đầu..
- Động lực : muốn sử dụng kiến thức của bản thân về AI để đóng góp cho cộng đồng ngưởi chơi Genshin Impact có một trải nghiệm suôn sẻ hơn vào giai đoạn đầu khi mọi thứ vẫn còn mới mẻ và khó khăn với người chơi.
- Là một dự án nhỏ và thú vị khi kết hợp niềm đam mê chơi game cùng với Computer Vision và xử lý ảnh theo thời gian thực 
### 🚀 Kế hoạch
# Dự định thực hiện dự án
- Sử dụng mô hình nhận diện vật thể (YOLOv8 chẳng hạn) để phát hiện quái vật trong khi đang chơi game hoặc video demo
- Khi mô hình phát hiện kẻ địch mạnh, lập tức phát cảnh báo bằng giọng nói
- Tiến hành chạy thử trên video ghi màn hình hoặc trực tiếp trong khi chơi game
# Các bước thực hiện
- Thu thập dữ liệu từ Hoyowiki những kẻ định mạnh (cấp tinh anh hoặc huyền thoại địa phương)
- Tiền xử lí dữ liệu : cắt, gán nhãn và chia nhóm dữ liệu thành tập huấn và kiểm thử
- Tinh chỉnh mô hình : sử dụng mô hình nhận diện YOLOv8 và tinh chỉnh nó
- Tích hợp cảnh báo : viết script phát hiện quái vật theo thời gian thực và phát âm thanh cảnh báo bằng TTS
- Đánh giá và thử nghiệm : kiểm tra độ chính xác cũng như tốc độ nhận nhiện kẻ địch
- Demo : chạy thử trong khi chơi game để minh họa khả năng phát hiện và cảnh báo kẻ địch.

### 📚 Tài liệu tham khảo
- Roboflow Blog – Tutorials on Object Detection and Dataset Annotation, [https://blog.roboflow.com/tag/object-detection/]
- Hoyoverse : Genshin Monsters List, [https://genshin-impact.fandom.com/wiki/Enemy/List]
- OpenCV Library – Computer Vision and Image Processing in Python.
- Ultralytics. YOLOv8 Object Detection Documentation, [https://docs.ultralytics.com/]
