# Đồ án Phân Tích & Thiết Kế Hệ Thống Quản Lý Tình Hình Học Tập Của Sinh Viên

## Mô tả đầu bài
Đồ án này thực hiện phân tích và thiết kế hệ thống quản lý tình hình học tập của sinh viên tại các cơ sở giáo dục. Hệ thống sẽ giúp quản lý thông tin sinh viên, điểm số, lịch học, và các báo cáo liên quan đến quá trình học tập của sinh viên. Các chức năng chính của hệ thống bao gồm:

- Quản lý thông tin sinh viên
- Quản lý điểm số và kết quả học tập
- Quản lý lớp học và học kỳ
- Phân tích và báo cáo tình hình học tập của sinh viên
- Gửi thông báo về lịch học, kỳ thi, và các sự kiện quan trọng khác

## Triển khai yêu cầu 1: Dàn ý

### 1.Giới thiệu về hệ thống
- **Mục đích:** Hệ thống quản lý tình hình học tập của sinh viên nhằm hỗ trợ các giảng viên, quản trị viên và sinh viên trong việc theo dõi, đánh giá và cải thiện kết quả học tập.
- **Đối tượng sử dụng:** Sinh viên, giảng viên, quản trị viên.
- **Các tính năng chính:** Quản lý thông tin sinh viên, quản lý điểm số, báo cáo kết quả học tập, gửi thông báo.

### 2.Phân tích yêu cầu
- **Quản lý sinh viên:**
  - Thêm, sửa, xóa thông tin sinh viên.
  - Quản lý lớp học và môn học mà sinh viên tham gia.
- **Quản lý điểm số:**
  - Nhập điểm môn học cho sinh viên.
  - Theo dõi điểm số của sinh viên qua các học kỳ.
  - Tính toán điểm trung bình của sinh viên.
- Thông báo và nhắc nhở:
  - Gửi thông báo về kỳ thi, kết quả học tập, và các sự kiện quan trọng khác.
-Báo cáo và phân tích:
  - Tạo báo cáo về tình hình học tập của sinh viên.
  - Cung cấp các biểu đồ phân tích tình hình học tập.

### 3. **Thiết kế hệ thống**
- **Cấu trúc hệ thống:**
  - Giao diện người dùng (Frontend) sẽ được xây dựng với JavaScript.
  - Backend sử dụng Node.js để xử lý logic.
  - Cơ sở dữ liệu MySQL để lưu trữ thông tin sinh viên, điểm số, lớp học, v.v.
- Các phần chính của hệ thống:
  - Giao diện người dùng : Dành cho sinh viên, giảng viên và quản trị viên.
  - Cơ sở dữ liệu: Lưu trữ tất cả thông tin về sinh viên, điểm số, lịch học.
  - API:Cung cấp các API để xử lý yêu cầu từ người dùng và quản lý dữ liệu.

### 4. Lộ trình phát triển
- **Bước 1:Thu thập yêu cầu và phân tích hệ thống.
- **Bước 2: Thiết kế cơ sở dữ liệu và giao diện người dùng.
- **Bước 3: Phát triển và kiểm thử hệ thống.
- **Bước 4: Triển khai và bảo trì hệ thống.

## Công nghệ sử dụng
- **Frontend:JavaScrip.
- **Backend:** Node.js.
- **Cơ sở dữ liệu: MySQL.

