#Nhóm 10 Đề Tài 20: Xây dựng phần mềm quản lý dịch vụ chạy quảng cáo trên mạng internet

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
