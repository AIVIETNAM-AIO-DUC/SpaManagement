# Ứng dụng quản lý Spa (Spa Management)

## I. Mô tả

Spa Management app là dự án "Bài tập lớn môn Công nghệ phần mềm". Mục tiêu là phát triển ứng dụng đáp ứng các nghiệp vụ quản lý tiệm Spa, bao gồm quản lý phân quyền người dùng (Quản lý, Lễ tân, Kỹ thuật viên, Thu ngân), đặt lịch hẹn, quản lý dịch vụ và sản phẩm, thanh toán hóa đơn cũng như thống kê doanh thu.

## II. Thành viên nhóm

| Họ tên               | Vai trò              | 
|----------------------|----------------------|
| Nguyễn Huy Mạnh Tuấn | Developer            |
| Nguyễn Văn Đức       | Developer            |

## III. Công nghệ sử dụng

- Web framework: Flask
- Database: MySQL
- ORM: Flask-SQLAlchemy
- UI/UX: Jinja2, Flask-Admin
- Khác: Flask-Login (Authentication), Cloudinary (Lưu trữ ảnh)
- Version control: Git + GitHub

## IV. Các phiên bản release

| Mã phiên bản | Nội dung | Trạng thái | 
|--------------|----------|------------|
| 1.0          | Hoàn thiện tính năng cơ bản |            |

## V. Cấu trúc tổng quan
<pre>
SpaManagement/
├── spaapp/
│   ├── static/ 
│   ├── templates/ 
│   ├── data/
│   ├── __init__.py 
│   ├── index.py            
│   ├── app.py            
│   ├── admin.py
│   ├── dao.py
│   ├── models.py
│   └── seed.py
├── .venv/
├── README.md                         
├── requirements.txt   
└── LICENSE
</pre>

## VI. Cài đặt và chạy

### 1. Yêu cầu

- Python 3.8 trở lên
- Git
- MySQL

### 2. Hướng dẫn chạy

<pre>
Bước 1: Đứng tại thư mục gốc của repository
Bước 2: Mở command prompt và tạo/kích hoạt môi trường ảo (ví dụ: .venv\Scripts\activate)
Bước 3: Cài đặt các thư viện cần thiết: pip install -r requirements.txt
Bước 4: Chạy ứng dụng: python -m spaapp.index (hoặc tuỳ thuộc vào file chạy chính của bạn)
</pre>

### 3. Truy cập

- Local: http://localhost:5000 (Port mặc định của Flask)

## VII. Tài liệu
