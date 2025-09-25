# LTM-1604 Gửi tin nhắn Broadcast qua UDP
<h2 align="center">
    <a href="https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin">
        🎓 Faculty of Information Technology (DaiNam University)
    </a>
</h2>

<h2 align="center">
    Ứng dụng Gửi Tin Nhắn broadcast Qua UDP
</h2>

<div align="center">
    <p align="center">
        <img src="docs/aiotlab_logo.png" alt="AIoTLab Logo" width="170"/>
        <img src="docs/fitdnu_logo.png" alt="FIT Logo" width="180"/>
        <img src="docs/dnu_logo.png" alt="DaiNam University Logo" width="200"/>
    </p>

[![AIoTLab](https://img.shields.io/badge/AIoTLab-green?style=for-the-badge)](https://www.facebook.com/DNUAIoTLab)
[![Faculty of Information Technology](https://img.shields.io/badge/Faculty%20of%20Information%20Technology-blue?style=for-the-badge)](https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin)
[![DaiNam University](https://img.shields.io/badge/DaiNam%20University-orange?style=for-the-badge)](https://dainam.edu.vn)

</div>

## 1. Giới thiệu hệ thống

**Ứng dụng Nhắn Tin** được xây dựng theo mô hình **Client–Server**, cho phép nhiều người dùng trò chuyện trực tuyến với nhau thông qua giao diện web.  

🔍 Các Tính Năng Nổi Bật:

Nhắn tin theo thời gian thực:
Hệ thống sử dụng công nghệ WebSocket (hoặc thư viện tương đương như Socket.IO) để đảm bảo việc gửi và nhận tin nhắn diễn ra tức thì, không cần tải lại trang.

Hỗ trợ nhiều phòng trò chuyện (Chat rooms):
Người dùng có thể dễ dàng tạo mới hoặc tham gia các phòng chat sẵn có, phục vụ cho việc trao đổi theo nhóm, theo chủ đề hoặc theo mục đích sử dụng riêng.

Quản lý người dùng online:
Giao diện hiển thị danh sách người dùng đang trực tuyến theo thời gian thực, giúp người dùng biết được ai đang hoạt động và sẵn sàng trò chuyện.

Giao diện người dùng thân thiện và trực quan:
Thiết kế tối giản, hiện đại, tập trung vào trải nghiệm người dùng với bố cục rõ ràng, thao tác đơn giản, phù hợp với cả người mới và người dùng thành thạo.

Tương thích đa nền tảng:
Ứng dụng có thể truy cập dễ dàng từ máy tính, máy tính bảng hoặc điện thoại thông minh thông qua trình duyệt, không cần cài đặt phần mềm bổ sung.
---

## 🔧 2. Công nghệ & Ngôn ngữ sử dụng

[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.oracle.com/java/technologies/javase-downloads.html)  
[![UDP](https://img.shields.io/badge/UDP%20Multicast-00599C?style=for-the-badge&logo=socket.io&logoColor=white)](https://docs.oracle.com/javase/tutorial/networking/datagrams/)   
[![Eclipse](https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge&logo=eclipseide&logoColor=white)](https://www.eclipse.org/)  
[![NetBeans](https://img.shields.io/badge/NetBeans-1B6AC6?style=for-the-badge&logo=apachenetbeanside&logoColor=white)](https://netbeans.apache.org/)  


•	**Java**: Ngôn ngữ lập trình phổ biến, được dùng để phát triển ứng dụng trên nhiều nền tảng khác nhau.

•	**UDP Multicast**: Giao thức mạng giúp truyền dữ liệu đến nhiều người nhận mà không làm quá tải mạng, dùng trong phát sóng trực tuyến.

•	**Eclipse**: IDE mã nguồn mở, chủ yếu dùng để phát triển ứng dụng Java, hỗ trợ nhiều ngôn ngữ qua plugin.

•	**NetBeans**: IDE mã nguồn mở, dễ sử dụng, hỗ trợ phát triển ứng dụng Java và các ngôn ngữ khác như PHP, C++.


## 🚀 3. Một số hình ảnh

### Giao diện đăng nhập
![Cấu trúc chương trình](demo/1.jpeg)

### Giao diện chat room
![Luồng xử lý](demo/2.jpeg)

### Giao diện tạo room
![Giao diện](demo/3.jpeg)

---

## ⚙️ 4. Các bước cài đặt & chạy

🔧 **Bước 1. Chuẩn bị môi trường**
- Cài đặt **JDK 8 hoặc 11**.  
- IDE khuyến nghị: **Eclipse** hoặc **NetBeans**.  

📦 **Bước 2. Tải project**
- Clone repository từ GitHub:  
  ```bash
  git clone https://github.com/username/udp-multicast-chat.git
  cd udp-multicast-chat


---
## 👨‍💻 5 . Liên hệ (cá nhân)

Contact me:  

📌 **Họ tên:** [Hoàng Anh Tú] – CNTT K16-04  
📌 **Khoa:** Công nghệ thông tin – Trường Đại học Đại Nam  
📌 **Email:** [anhtu271024@gmail.com]  
