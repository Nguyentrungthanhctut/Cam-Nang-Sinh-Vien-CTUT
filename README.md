# 🎓 Cẩm Nang Sinh Viên CTUT (CTUT × Thanhdev Hub)

**Cẩm Nang Sinh Viên CTUT** là ứng dụng web tiện ích hỗ trợ học tập dành cho sinh viên **Trường Đại học Kỹ thuật - Công nghệ Cần Thơ (CTUT)** — giúp tra cứu khung giờ tiết học theo thời gian thực, tính điểm học phần chuẩn quy chế tín chỉ và dự báo điểm thi cuối kỳ thông minh.

![CTUT x Thanhdev Hub Logo](./logo.jpg)

---

## ✨ Tính năng chính

- **Đồng hồ thời gian thực & Nhận diện tiết học tự động:** Tự động đối chiếu giờ hiện tại để hiển thị chính xác đang ở **Tiết học nào (Tiết 1 – Tiết 13)**, **Giờ nghỉ giải lao 15 phút** hay **Ngoài giờ học chính quy**.
- **Tra cứu Thời gian dạy học chuẩn CTUT:** Bảng khung giờ chi tiết 3 buổi **Sáng – Chiều – Tối** cùng mốc thời gian nghỉ giữa giờ sau Tiết 3 và Tiết 8.
- **Tính điểm Học phần & Dự báo điểm Cuối kỳ thông minh:**
  - Tự động đồng bộ tỷ lệ trọng số **Giữa kỳ / Cuối kỳ** (tổng = 100%).
  - Quy đổi tức thì từ **Thang điểm 10** sang **Điểm chữ (`A+` đến `F`)**, **Thang điểm 4 (`4.0` đến `0.0`)** và **Xếp loại học phần**.
  - Nhập điểm Giữa kỳ và chọn mục tiêu mong muốn (`A+`, `A`, `B+`, `B`, `C+`, `C`, `D`) để hệ thống tính toán số điểm thi Cuối kỳ tối thiểu cần đạt kèm lời khuyên ôn tập.
- **Quản lý danh sách môn học & Tính GPA Học kỳ:** Lưu trữ các môn học trên trình duyệt (`localStorage`) và tự động tính **Điểm trung bình chung học kỳ (GPA Hệ 4)** kèm xếp loại học kỳ.
- **Bảng quy đổi Thang điểm chuẩn CTUT:** Tra cứu nhanh 2 bảng quy định đánh giá loại học phần (tích lũy / không đạt) và bảng quy đổi GPA hệ số 4.

---

## 📂 Cấu trúc thư mục

Đảm bảo tệp `logo.jpg` nằm cùng cấp với `index.html` để hiển thị đầy đủ Favicon, cụm logo hợp tác trên Header, thẻ Tác giả và Footer:

```text
CTUT-Student-Handbook/
├── index.html      # Mã nguồn giao diện (Tailwind CSS) & logic tính điểm JavaScript
├── logo.jpg        # Logo thương hiệu hợp tác Thanhdev Hub
└── README.md       # Tài liệu giới thiệu dự án
