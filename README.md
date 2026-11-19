# 🎨 Thiết kế giao diện – Cổng thông tin sinh viên Khoa CNTT

Bản thiết kế UI (Figma) cho **cổng thông tin sinh viên** của Khoa Công nghệ Thông tin – Trường Cao đẳng Kỹ thuật Cao Thắng. Sinh viên dùng cổng này để xem thông báo, học phần, bài tập, điểm, thời khóa biểu và thanh toán học phí.

> Môn học: **Thiết kế giao diện** · Lớp: **CĐ CNTT24WEBC**

---

## 📁 Cấu trúc repo

```
Figma/
├── design/
│   └── Thietke.fig      # File Figma gốc (~7 MB)
└── README.md
```

## 🔗 Xem bản thiết kế

- **Figma online:** [Mở trên Figma](https://www.figma.com/design/...) <!-- dán link Share vào đây -->
- **File gốc:** [`design/Thietke.fig`](design/Thietke.fig)

### Cách mở file `.fig`
1. Tải `design/Thietke.fig` về máy (bấm vào file, rồi bấm **Download raw file**).
2. Vào [figma.com](https://www.figma.com), mở trang **Drafts** hoặc **Home**.
3. Kéo thả file `.fig` vào cửa sổ Figma (hoặc vào **Import**).

---

## 🖥️ Các màn hình chính

| Nhóm | Màn hình | Mô tả |
|---|---|---|
| Tài khoản | **Đăng nhập** | Đăng nhập bằng Gmail sinh viên và mật khẩu, có mục quên mật khẩu |
| Tổng quan | **Trang chủ** | Thanh menu, thanh tìm kiếm và các thẻ chức năng nhanh |
| | **Thông tin sinh viên** | Họ tên, ngày sinh, quê quán, hệ đào tạo, giáo viên chủ nhiệm |
| Thông báo | **Thông báo** | Thông báo từ giáo viên và từ nhà trường, có tệp đính kèm và mục "Các tin khác" |
| Học tập | **Kế hoạch học tập** | Lịch và kế hoạch đào tạo theo năm học |
| | **Thời khóa biểu** | Lịch học theo tuần |
| | **Danh sách học phần** | Mã học phần, tên môn, giảng viên, trạng thái đăng ký |
| | **Giáo trình** | Bài giảng theo môn, tài liệu đính kèm |
| | **Bài tập được giao** | Đề bài, nút *Bắt đầu làm bài*, nộp file (Submit file) |
| | **Điểm kiểm tra** | Xem điểm và xem lại bài làm |
| Học vụ | **Đăng ký học lại** | Bộ lọc theo học kỳ và ngành, tìm theo tên môn |
| | **Giấy tờ xác nhận** | Yêu cầu giấy tờ từ phòng đào tạo |
| Tài chính | **Thanh toán học phí** (3 bước) | ① Các khoản phải thu → ② Chọn phương thức thanh toán → ③ Thanh toán thành công |

## 🧩 Components

- **Topbar** và **Footer** dùng chung cho mọi trang
- **Button** (`btn-primary`) với các trạng thái *Default* và *Hover*
- **Card trang chủ**, **Kết quả tìm kiếm**, **Thanh công cụ**
- Các **prototype flow** để chuyển giữa các màn hình

## 🎨 Style guide

| Thành phần | Giá trị |
|---|---|
| Font chính | **Roboto** (Light, Regular, Medium, SemiBold, Bold) |
| Font phụ | **Inter** (SemiBold, Bold), dùng cho tiêu đề và nút |
| Icon | [Iconify](https://iconify.design) (Material Symbols, MDI, Mingcute, Carbon, Icon Park), Icons8 |

---



## 📌 Ghi chú

- Dữ liệu trong bản thiết kế (tên giáo viên, môn học, số tiền…) chỉ là **dữ liệu mẫu**.
- Mỗi lần cập nhật thiết kế: dùng **File → Save local copy…** trong Figma, ghi đè `design/Thietke.fig`, rồi commit và push.

---

© 2026 · Khoa Công nghệ Thông tin – Trường Cao đẳng Kỹ thuật Cao Thắng
