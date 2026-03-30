# Hệ thống Quản lý Ký túc xá

## Giới thiệu
Hệ thống Quản lý Ký túc xá là một ứng dụng desktop được xây dựng nhằm mô phỏng các chức năng cơ bản trong việc quản lý ký túc xá.

Dự án hướng đến:
- Áp dụng kiến thức lập trình vào bài toán thực tế  
- Rèn luyện tư duy phân tích nghiệp vụ theo định hướng Business Analyst  
- Xây dựng nền tảng cho các hệ thống quản lý hoàn chỉnh hơn  

---

## Mục tiêu
- Phân tích bài toán quản lý ký túc xá  
- Xác định các tác nhân sử dụng hệ thống  
- Chuyển đổi yêu cầu nghiệp vụ thành chức năng hệ thống  
- Thiết kế luồng xử lý (đăng nhập, đăng ký, truy cập hệ thống)  
- Hiểu mối liên hệ giữa giao diện, xử lý logic và dữ liệu  

---

## Chức năng chính
- Đăng nhập hệ thống  
- Đăng ký tài khoản  
- Hiển thị giao diện sau khi đăng nhập  
- Thiết kế giao diện bằng Qt Designer  
- Tách riêng phần giao diện (.ui) và xử lý (.py)  

---

## Công nghệ sử dụng
- Python  
- PyQt6  
- Qt Designer  
- PyCharm  
- GitHub  

---

## Cấu trúc dự án
```bash
Dormitory-Management-System/
│
├── ui/                        # Giao diện (.ui)
│   ├── login.ui
│   ├── register.ui
│   └── dashboard.ui
│
├── views/                     # Xử lý giao diện
│   ├── login_view.py
│   ├── register_view.py
│   └── dashboard_view.py
│
├── models/                    # Dữ liệu
│   └── user.py
│
├── controllers/               # Xử lý nghiệp vụ
│   └── auth_controller.py
│
├── resources/                 # Tài nguyên (ảnh, icon)
│
├── main.py                   # File chạy chính
├── requirements.txt
└── README.md
```

---

## Phân tích theo hướng nghiệp vụ
- Tác nhân: Nhân viên quản lý ký túc xá  

- Các trường hợp sử dụng chính:
  - Đăng nhập hệ thống  
  - Đăng ký tài khoản  

- Dữ liệu xử lý:
  - Thông tin tài khoản người dùng  

- Mục tiêu hệ thống:
  - Hỗ trợ quản lý và xác thực người dùng  

---

## Hướng phát triển
- Tích hợp cơ sở dữ liệu (SQLite hoặc MySQL)  
- Mở rộng chức năng quản lý phòng và sinh viên  
- Xây dựng báo cáo và thống kê  
- Thiết kế Use Case Diagram, BPMN  
- Phát triển dashboard hỗ trợ quản lý  

---

## Tác giả
Nguyễn Trần Yên Đan - K244161778  

Nhóm Firefly
Ngành Hệ thống thông tin quản lý - chuyên ngành Kinh doanh số và Trí tuệ nhân tạo  
Khoa Hệ thống Thông tin  
Trường Đại học Kinh tế – Luật, ĐHQG-HCM  

---

## Ghi chú
Dự án được xây dựng nhằm mục đích học tập và phát triển kỹ năng cá nhân.
