# 📰 Sandbox News — Nền Tảng Phân Tích Chiến Lược & Dòng Tiền
> **URL Hệ Thống:** `https://www.sandboxstartup.vn/` (Hoặc tên miền vận hành chính thức)
> **Sản phẩm thuộc:** The Sandbox Entrepreneurs Vietnam

Sandbox News là một trang báo điện tử tối giản, giao diện tạp chí bất đối xứng cổ điển, chuyên phân phối các bài phân tích chuyên sâu về **M&A, Định giá doanh nghiệp, Mô hình Holding, IPO, và Case Study tài chính**.

Hệ thống được thiết kế theo tư duy **Lean Operations (Vận hành tinh gọn)**: Triệt tiêu hoàn toàn hệ thống quản trị (Backend/Dashboard CMS) phức tạp, vận hành tự động thông qua luồng dữ liệu đóng gói từ AI/Google Sheets.

---

## 🛠️ Kiến Trúc Hệ Thống (Architecture & Data Flow)

Hệ thống hoạt động theo mô hình **Serverless Jamstack Tối Giản**:
[Google Sheets Database] ──(Dữ liệu bài viết/Markdown)
│
▼
[Google Apps Script API] ──(Cổng biên dịch JSON Endpoint)
│
▼
[Vanilla Front-end Client] ──(Xử lý State, Render HTML & Markdown nội bộ)
