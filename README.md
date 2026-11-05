# My-CV – Portfolio cá nhân của Nguyễn Đại Đỉnh

## 1. Giới thiệu dự án
Dự án `My-CV` là một trang portfolio cá nhân được xây dựng bằng HTML5 và CSS3, nhằm giới thiệu thông tin cơ bản về bản thân, kỹ năng, các dự án tiêu biểu và thông tin liên hệ. Trang được thiết kế theo hướng hiện đại, tối ưu cho màn hình điện thoại, máy tính bảng và máy tính để bàn, giúp người xem dễ dàng nắm bắt thông tin nhanh chóng.

Website này phù hợp cho việc giới thiệu cá nhân, hồ sơ kỹ thuật viên/Frontend Developer, cũng như dùng làm template CV/portfolio cơ bản để tùy biến theo nhu cầu riêng.

## 2. Tên dự án
My-CV

## 3. Mô tả
Dự án là một trang web CV/Portfolio cá nhân cho Nguyễn Đại Đỉnh, một Frontend Developer & UI Enthusiast. Trang web trình bày:
- Giới thiệu bản thân
- Kỹ năng chính
- Dự án tiêu biểu
- Thông tin liên hệ để hợp tác hoặc ứng tuyển

Các phần nội dung được bố cục rõ ràng, có thiết kế màu sắc nhẹ, dễ đọc và có tính thẩm mỹ cao.

## 4. Chức năng chính
- Hiển thị banner/hero giới thiệu cá nhân
- Trình bày thông tin nghề nghiệp và mục tiêu
- Danh sách kỹ năng chuyên môn
- Hiển thị các dự án tiêu biểu theo dạng thẻ card
- Liên kết đến GitHub và email
- Thiết kế responsive cho nhiều kích thước màn hình
- Hỗ trợ di chuyển nhanh giữa các section bằng điều hướng menu

## 5. Công nghệ sử dụng
Dự án sử dụng các công nghệ cơ bản sau:
- HTML5
- CSS3
- Flexbox và CSS Grid
- Responsive Design
- Git & GitHub
- Visual Studio Code
- Docker (tùy chọn cho triển khai container)

## 6. Cấu trúc thư mục
```text
My-CV/
├── index.html                 # File giao diện chính
├── assets/
│   ├── css/
│   │   └── styles.css        # File CSS chính
│   └── img/
│       ├── avatar.jpg        # Ảnh đại diện
│       └── icon-trang-chu.png
├── README.md                 # Tài liệu hướng dẫn
├── BAOCAO-A2.1.docx         # Tài liệu báo cáo (nếu có)
└── docx/
    └── RELEASENOTE.md
```

## 7. Yêu cầu môi trường
Để chạy dự án, bạn cần:
- Hệ điều hành: Windows 10/11, macOS 12+, Linux (Ubuntu 20.04+ hoặc bản phân phối tương đương)
- Trình duyệt: Google Chrome, Microsoft Edge, Firefox hoặc Safari
- Một trình soạn thảo mã như: Visual Studio Code
- Git (nếu muốn clone repository)
- Python 3 (tùy chọn, dùng để chạy máy chủ local nhanh)
- Docker Desktop (tùy chọn, nếu triển khai bằng container)

## 8. Cài đặt
### 8.1. Clone dự án
```bash
git clone <URL_REPOSITORY>
cd My-CV
```

### 8.2. Mở trực tiếp
Bạn có thể mở file `index.html` trực tiếp bằng trình duyệt mà không cần cài đặt phụ trợ.

### 8.3. Cài đặt trình soạn thảo và công cụ hỗ trợ
- Tải và cài đặt Visual Studio Code: https://code.visualstudio.com/
- Nếu cần, cài đặt Git: https://git-scm.com/
- Nếu muốn dùng local server, cài đặt Python 3: https://www.python.org/

## 9. Cấu hình
Dự án là một trang tĩnh nên cấu hình cơ bản rất đơn giản.

### 9.1. Thay đổi thông tin cá nhân
Mở file `index.html` và chỉnh sửa các nội dung sau:
- Tên: `Nguyễn Đại Đỉnh`
- Mô tả nghề nghiệp: `Frontend Developer & UI Enthusiast`
- Email liên hệ
- GitHub
- Thông tin dự án, kỹ năng, tiêu đề section

### 9.2. Thay đổi giao diện
Mở file `assets/css/styles.css` để tùy chỉnh:
- Màu chủ đạo
- Khoảng cách giữa các section
- Kích thước chữ
- Hình dạng button
- Layout responsive

Các biến màu chính được định nghĩa trong phần `:root` của file CSS.

### 9.3. Thay đổi hình ảnh
- Ảnh avatar: `assets/img/avatar.jpg`
- Icon trang chủ: `assets/img/icon-trang-chu.png`

## 10. Hướng dẫn chạy dự án
### 10.1. Windows
#### Cách 1: Mở trực tiếp
1. Vào thư mục dự án
2. Double click vào file `index.html`
3. Trình duyệt sẽ mở trang portfolio

#### Cách 2: Chạy bằng máy chủ local
Mở Command Prompt hoặc PowerShell và chạy:
```powershell
cd "D:\Bài Tập\Thiết kế web và triển khai hệ thống phần mềm\NDD03BT\Chương 8\My-CV"
python -m http.server 8000
```
Sau đó mở trình duyệt và truy cập:
```text
http://localhost:8000
```

### 10.2. macOS
Mở Terminal và thực hiện:
```bash
cd /đường/dẫn/đến/My-CV
python3 -m http.server 8000
```
Sau đó mở trình duyệt và truy cập:
```text
http://localhost:8000
```

### 10.3. Linux
Mở Terminal và chạy:
```bash
cd /đường/dẫn/đến/My-CV
python3 -m http.server 8000
```
Hoặc nếu bạn muốn dùng server có sẵn:
```bash
sudo apt update
sudo apt install python3
cd /đường/dẫn/đến/My-CV
python3 -m http.server 8000
```
Truy cập:
```text
http://localhost:8000
```

### 10.4. Docker
Nếu muốn chạy dự án trong Docker, bạn có thể tạo một `Dockerfile` như sau:

```dockerfile
FROM nginx:alpine
COPY . /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
```

Sau đó chạy các lệnh sau:
```bash
docker build -t my-cv .
docker run -d -p 8080:80 --name my-cv-container my-cv
```
Mở trình duyệt và truy cập:
```text
http://localhost:8080
```

Nếu cần triển khai nhiều hơn, bạn có thể dùng `docker-compose.yml` với cấu hình tương tự.

## 11. Chạy thử
Sau khi server khởi động thành công:
- Mở browser
- Truy cập vào đường dẫn `http://localhost:8000` hoặc `http://localhost:8080` (nếu dùng Docker)
- Kiểm tra giao diện: phần giới thiệu, kỹ năng, dự án, liên hệ
- Xác nhận bố cục responsive hoạt động trên màn hình điện thoại và desktop

## 12. Lưu ý khi phát triển tiếp
- Không cần framework phức tạp cho dự án này
- Nếu muốn nâng cấp lên phiên bản động, có thể chuyển sang React/Vite hoặc Next.js
- Có thể thêm phần carousel, form liên hệ, dark mode, hoặc animation
- Tối ưu SEO bằng cách thêm thẻ meta rõ ràng và cấu trúc heading hợp lý

## 13. Thông tin liên hệ
- Họ tên: Nguyễn Đại Đỉnh
- Email: `zinshin543@gmail.com`
- GitHub: `https://github.com/GOOGOOGAGA`
- Mục tiêu: Mở rộng cơ hội hợp tác, thực tập và vị trí Frontend Developer

## 14. Kết luận
Dự án `My-CV` là một website portfolio đơn giản nhưng đẹp, phù hợp để giới thiệu cá nhân và kỹ năng kỹ thuật. Với cấu trúc rõ ràng và dễ tùy biến, dự án có thể được mở rộng thêm nhiều tính năng mới trong tương lai mà không cần thay đổi toàn bộ nền tảng.

## 15. Tài liệu tham khảo nhanh
- HTML5: https://developer.mozilla.org/en-US/docs/Web/HTML
- CSS3: https://developer.mozilla.org/en-US/docs/Web/CSS
- GitHub: https://github.com/
- Docker: https://www.docker.com/

