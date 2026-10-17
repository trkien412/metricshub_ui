# Nhật ký sử dụng AI (Prompt Log)

## Prompt 1 – Phân tích lỗi layout
**Prompt:** So sánh Flexbox và CSS Grid. Vì sao Navbar có nội dung dài nên dùng Flexbox, còn Dashboard có widget chiếm nhiều hàng/cột nên dùng Grid?

**Tóm tắt kết quả:** Flexbox phù hợp sắp xếp một chiều và căn chỉnh theo nội dung. Grid quản lý cả hàng và cột, hỗ trợ `grid-column: span 2` và `grid-row: span 2`.

## Prompt 2 – Bootstrap Pricing
**Prompt:** Giải thích `col-sm-4` và `col-md-4` trong Bootstrap 5, đồng thời đề xuất cấu trúc 3 cột Pricing responsive.

**Tóm tắt kết quả:** `col-md-4` tạo cột rộng 4/12 từ breakpoint md trở lên. Kết hợp `col-12 col-md-4` để mỗi gói xếp toàn chiều rộng trên mobile và thành 3 cột trên desktop.

## Prompt 3 – Responsive và khoảng cách
**Prompt:** Làm thế nào để Navbar không tràn trên màn hình 375px và dùng `gap` thay cho các margin rời rạc?

**Tóm tắt kết quả:** Dùng `flex-wrap: wrap`, đưa menu xuống hàng riêng ở màn hình nhỏ; dùng `gap` cho khoảng cách giữa các phần tử trong Flexbox và CSS Grid.

## Prompt 4 – Kiểm thử
**Prompt:** Đưa ra checklist kiểm thử giao diện MetricsHub ở desktop, tablet và mobile.

**Tóm tắt kết quả:** Kiểm tra menu không đè logo, Dashboard chuyển về một cột ở mobile, Pricing xếp dọc dưới breakpoint md và không xuất hiện thanh cuộn ngang.
