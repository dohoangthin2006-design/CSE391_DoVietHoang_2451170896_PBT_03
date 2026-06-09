# CSE391_DoVietHoang_2451170896_PBT03

## Thông tin sinh viên

- **Họ và tên:** Đỗ Việt Hoàng
- **MSSV:** 2451170896
- **Môn học:** CSE391 - Nền tảng phát triển Web
- **Chủ đề:** CSS Core — Selectors, Box Model, Inheritance & Cascade

---

## Giới thiệu

Bài tập thực hành PBT03 tập trung vào các kiến thức nền tảng của CSS:

- CSS Selectors
- Box Model
- Inheritance & Cascade
- Specificity
- CSS Layout Debugging

---

## Cấu trúc thư mục

```text
CSE391_DoVietHoang_2451170896_PBT03/
│
├── answers.md
├── selectors_test.html
│
├── profile.html
├── style.css
│
├── boxmodel_lab.html
├── boxmodel.css
│
├── specificity.html
├── specificity.css
│
├── debug_layout.html
├── debug_layout.css
│
├── screenshots/
│   ├── selectors_test.png
│   ├── boxmodel_content_box.png
│   ├── boxmodel_border_box.png
│   ├── layout_3_columns.png
│   ├── specificity_result.png
│   └── cascade_result.png
│
├── videos/
│   └── PBT03_DoVietHoang_2451170896.mp4
│
└── README.md
```

---

## Nội dung bài làm

### 1. answers.md

Bao gồm:

- Phần A — Đọc hiểu
- Phần C — Debug & Suy luận
- Giải thích Selectors
- Tính toán Box Model
- Specificity
- Cascade & Inheritance

---

### 2. selectors_test.html

Kiểm chứng kết quả của các CSS Selectors:

- Element Selector
- Class Selector
- ID Selector
- Descendant Selector
- Child Selector
- Attribute Selector
- Pseudo-class Selector

---

### 3. profile.html + style.css

Trang hồ sơ cá nhân sử dụng External CSS.

#### Kỹ thuật sử dụng

- Universal Selector (`*`)
- Element Selector
- Class Selector
- ID Selector
- Descendant Selector
- Pseudo-class (`:hover`)
- Zebra Table (`nth-child`)
- Gradient Background
- Border Box Reset

---

### 4. boxmodel_lab.html + boxmodel.css

Thực hành Box Model.

#### Nội dung

##### Content-box vs Border-box

- So sánh kích thước thực tế
- Đo bằng DevTools
- Phân tích padding và border

##### Layout 3 cột

- Sidebar
- Content
- Ads

Chứng minh sự khác biệt khi sử dụng:

```css
box-sizing: content-box;
```

và

```css
box-sizing: border-box;
```

---

### 5. specificity.html + specificity.css

Thực hành độ ưu tiên của CSS.

#### Nội dung

- 10 CSS Rules
- So sánh Specificity
- Kiểm tra thứ tự Cascade
- Kiểm tra tác động của `!important`

---

### 6. debug_layout.html + debug_layout.css

Phân tích lỗi layout.

#### Nội dung

- Tính toán chiều rộng thực tế
- Chứng minh layout bị vỡ
- Sửa bằng:

##### Cách 1

```css
box-sizing: border-box;
```

##### Cách 2

Điều chỉnh width thủ công để tổng kích thước không vượt quá container.

---

## Công nghệ sử dụng

- HTML5
- CSS3
- Chrome DevTools

---

## Hướng dẫn chạy

Mở trực tiếp các file HTML bằng trình duyệt:

```text
selectors_test.html
profile.html
boxmodel_lab.html
specificity.html
debug_layout.html
```

Hoặc sử dụng VS Code + Live Server:

1. Mở project bằng VS Code
2. Chuột phải file HTML
3. Chọn **Open with Live Server**

---

## Screenshots

Các ảnh chụp màn hình được lưu trong thư mục:

```text
screenshots/
```

Bao gồm:

- Kết quả Selectors
- DevTools Box Model Diagram
- Layout 3 cột
- Specificity Battle
- Cascade Puzzle

---

## Video OBS

### Chủ đề

Chứng minh sự khác nhau giữa:

- Content Box
- Border Box

### Nội dung

- Tạo 2 div từ đầu
- Tính toán kích thước bằng miệng
- Kiểm tra bằng DevTools
- Chứng minh Margin Collapse
- Giải thích lý do sử dụng:

```css
* {
    box-sizing: border-box;
}
```

Video được nộp trong:

```text
videos/
```

hoặc link video được ghi trong:

```text
answers.md
```

---

## Kiến thức đã áp dụng

### CSS Selectors

- Element
- Class
- ID
- Descendant
- Child
- Attribute
- Pseudo-class

### Box Model

- Content
- Padding
- Border
- Margin
- Margin Collapse

### Cascade

- Inheritance
- Specificity
- Source Order
- `!important`

---

## Yêu cầu đã hoàn thành

- [x] answers.md
- [x] selectors_test.html
- [x] profile.html + style.css
- [x] boxmodel_lab.html + boxmodel.css
- [x] specificity.html + specificity.css
- [x] debug_layout.html + debug_layout.css
- [x] Screenshots
- [x] Video OBS
- [x] GitHub Repository
- [x] Tối thiểu 4 commits

---

## Kết luận

Qua bài tập PBT03, em đã hiểu rõ:

- Cách CSS lựa chọn phần tử bằng selectors
- Cơ chế Box Model và box-sizing
- Margin Collapse
- Specificity và Cascade
- Các lỗi layout thường gặp và cách khắc phục

Đây là những kiến thức nền tảng quan trọng trước khi học Responsive Design, CSS Frameworks và JavaScript.
