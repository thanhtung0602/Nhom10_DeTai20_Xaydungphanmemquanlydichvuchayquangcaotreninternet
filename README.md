#Nhóm 10 Đề Tài 20: Xây dựng phần mềm quản lý dịch vụ chạy quảng cáo trên mạng internet

# Tuần 1
1. Giới thiệu tổng quan
Phần mềm quản lý dịch vụ chạy quảng cáo (Ads Management System) là một ứng dụng Desktop được xây dựng bằng Python. Hệ thống giúp các cá nhân, agency hoặc người làm affiliate marketing quản lý tập trung các chiến dịch quảng cáo trên đa nền tảng (Facebook, Google, TikTok), theo dõi tiến độ giải ngân, và xuất báo cáo hiệu suất một cách trực quan.

3. Mô tả các chức năng chi tiết
2.1. Module Tổng quan (Dashboard)
Cung cấp cái nhìn toàn cảnh về tình hình chạy quảng cáo thông qua các số liệu và biểu đồ:
Key Metrics (Chỉ số chính): Hiển thị các thông số quan trọng nhất bao gồm Tổng ngân sách (Total Budget), Số tiền đã chi tiêu (Spending), Ngân sách còn lại (Remaining) và Số lượng chiến dịch đang chạy (Active Campaigns).
Budget Allocation: Biểu đồ tròn thể hiện tỷ lệ phân bổ ngân sách trên các nền tảng (Facebook, Google Ads, TikTok Ads,...).
Top-Performing Campaigns: Bảng xếp hạng các chiến dịch đang mang lại hiệu quả tốt nhất dựa trên chi phí (Spend, CPC, CPA).
CPA Trend Chart: Biểu đồ đường theo dõi xu hướng chi phí chuyển đổi (CPA - Cost Per Action) theo thời gian, giúp đánh giá hiệu năng tổng thể của tài khoản.
System Activity & Alerts: Cập nhật các hoạt động gần đây của hệ thống và hiển thị các cảnh báo quan trọng (ví dụ: chiến dịch sắp hết ngân sách, CPA vượt ngưỡng an toàn).
<img width="1198" height="744" alt="Phác thảo " src="https://github.com/user-attachments/assets/b732925c-a97d-4f3f-9a6c-1726fe17a7ab" />

2.2. Module Quản lý Khách hàng (Client Management)
Hỗ trợ quản lý thông tin của các đối tác, nhãn hàng hoặc các tài khoản quảng cáo nội bộ:
Quản lý danh sách: Thêm mới, chỉnh sửa, hoặc xóa thông tin cơ bản của từng Client.
Tìm kiếm & Bộ lọc: Tìm kiếm khách hàng theo tên, hoặc lọc theo trạng thái hoạt động (Active, Paused, Completed) và nền tảng chạy quảng cáo.
Theo dõi ngân sách theo đối tác: Bảng thống kê chi tiết hiển thị tỷ lệ phân bổ nền tảng (Platform Allocation), tổng ngân sách được cấp, và số tiền đã tiêu của từng khách hàng.
<img width="1153" height="724" alt="Phác thảo client" src="https://github.com/user-attachments/assets/b35cda2c-24e5-415c-aac2-662252a32ebf" />

2.3. Module Quản lý Chiến dịch (Campaigns)
Nơi khởi tạo và điều hành trực tiếp các chiến dịch quảng cáo:
Tạo chiến dịch mới: Thiết lập tên chiến dịch, chọn khách hàng tương ứng, chọn nền tảng hiển thị, và nhập ngân sách (tổng/ngày).
Quản lý tài nguyên: Lưu trữ các liên kết tài nguyên (video, hình ảnh, link affiliate/sản phẩm) và ghi chú định hướng kịch bản quảng cáo.
Cập nhật trạng thái: Bật/tắt (Active/Pause) các chiến dịch một cách linh hoạt.

2.4. Module Theo dõi Hiệu suất (Tracking)
Nhập liệu và tính toán các chỉ số đo lường hiệu quả:
Cập nhật số liệu chi tiêu hàng ngày từ các nền tảng trả về.
Hệ thống hỗ trợ tính toán các chỉ số cơ bản như CPC (Cost Per Click), CPA (Cost Per Action), ROAS (Return on Ad Spend) dựa trên dữ liệu đầu vào.

2.5. Module Quản lý Báo cáo (Reports Management)
Tổng hợp dữ liệu và xuất file phục vụ cho việc đối soát:
Danh sách báo cáo: Quản lý các báo cáo đã tạo, hiển thị thông tin về loại báo cáo (ROAS, Spend, Engagement), kỳ báo cáo (Hàng tháng, Hàng quý), và trạng thái tạo (Generated/Draft).
Bộ lọc báo cáo: Tùy chỉnh xem báo cáo theo loại (Performance, Spend, ROI), theo nền tảng, và khoảng thời gian (Date Range).
Xuất file (Export): Hỗ trợ tải xuống dữ liệu báo cáo dưới định dạng file Excel (.xlsx) hoặc CSV để dễ dàng gửi cho đối tác hoặc lưu trữ.
<img width="1148" height="720" alt="Phác thảo báo cáo" src="https://github.com/user-attachments/assets/85e5fc08-4aee-4d72-9807-ddd6ba8cc733" />

# Tuần 2

1. Giao diện hệ thống đăng nhập
   <img width="1620" height="1034" alt="image" src="https://github.com/user-attachments/assets/1dec9a05-0945-457c-acbb-e311ee6de360" />
2. Giao diện Trang chủ
   <img width="1616" height="1029" alt="image" src="https://github.com/user-attachments/assets/e53cca81-2e00-4028-9f7b-67b42c03dcba" />
3. Giao diện quản lý chiến dịch
   <img width="1614" height="1025" alt="image" src="https://github.com/user-attachments/assets/d0cfe955-0656-4c6a-b428-1d1384775644" />
4. Giao diện quản lý Khách hàng, đối tác
   <img width="1622" height="1031" alt="image" src="https://github.com/user-attachments/assets/6d13fb6d-2149-4eff-9920-ade7d579ca3a" />
5. Giao diện theo dõi hiệu suất
   <img width="1625" height="1010" alt="image" src="https://github.com/user-attachments/assets/294077e5-8e7d-4430-b735-14d125113719" />
6. Giao diện báo cáo
   <img width="1619" height="1009" alt="image" src="https://github.com/user-attachments/assets/00994e4c-cf0f-4041-bd0d-97ca50864f5c" />

# Tuần 3

Để đáp ứng các chức năng trên giao diện, hệ thống sử dụng cơ sở dữ liệu **SQLite** và áp dụng mô hình **Lập trình Hướng đối tượng (OOP)**.

### 3.1. Thiết kế Cơ sở dữ liệu (Database Schema / ERD)
Cấu trúc được thiết kế mở rộng (SaaS-ready) bao gồm các bảng có liên kết chặt chẽ (Khóa chính - Khóa ngoại):
- `nguoi_dung`: Quản lý tài khoản và quyền truy cập.
- `khach_hang` & `hoa_don`: Quản lý thông tin đối tác và dòng tiền.
- `chien_dich`, `nhom_quang_cao`, `mau_quang_cao`: Bóc tách cấu trúc chiến dịch quảng cáo.
- `theo_doi_chi_tiet`: Lưu trữ số liệu hiệu suất (Click, Cost, Impression).
- `nhat_ky_he_thong`: Ghi nhận lịch sử thao tác của người dùng.

<img width="826" height="968" alt="image" src="https://github.com/user-attachments/assets/4b02be6e-60f9-4a27-a275-6a37c4b08682" />

### 3.2. Sơ đồ Lớp (Class Diagram)
Hệ thống gồm các lớp thực thể chính: `NguoiDung`, `KhachHang`, `ChienDich`, `TheoDoi`, `BaoCao`. 
Sơ đồ thể hiện rõ các mối quan hệ:
- **Kết hợp (Aggregation):** Giữa Khách hàng và Chiến dịch.
- **Cấu thành (Composition):** Giữa Chiến dịch và Theo dõi hiệu suất.
- **Phụ thuộc (Dependency):** Người dùng thao tác tạo Báo cáo.

<img width="2228" height="4272" alt="image" src="https://github.com/user-attachments/assets/c001062b-f566-4d07-8145-fa7d5c12deee" />

### 3.3. Cấu trúc mã nguồn hiện tại
- `app.py`: Đảm nhiệm 100% logic Giao diện (Frontend) bằng PyQt6.
- `database.py`: Đảm nhiệm tương tác Cơ sở dữ liệu và Business Logic (Backend).
