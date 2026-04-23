---
markmap:
  colorScheme: google
  math: katex
---

# 🎓 NHỊ THỨC NEWTON $(a + b)^n$ (TOÁN 10)

## 1. 📘 Công thức khai triển (với $n = 4, 5$)
### ✅ Khai triển cơ bản
- **Với $n = 4$:** $(a + b)^4 = C_4^0 a^4 + C_4^1 a^3b + C_4^2 a^2b^2 + C_4^3 ab^3 + C_4^4 b^4$
- **Với $n = 5$:** $(a + b)^5 = C_5^0 a^5 + C_5^1 a^4b + C_5^2 a^3b^2 + C_5^3 a^2b^3 + C_5^4 ab^4 + C_5^5 b^5$
### ✅ Các tính chất quan trọng
- **Số các số hạng:** Có $n + 1$ số hạng trong khai triển.
- **Số mũ:** Số mũ của $a$ giảm dần từ $n$ về $0$; số mũ của $b$ tăng dần từ $0$ lên $n$.
- **Tổng số mũ:** Trong mỗi số hạng, tổng số mũ của $a$ và $b$ luôn bằng $n$.
- **Hệ số:** Các hệ số cách đều số hạng đầu và cuối thì bằng nhau ($C_n^k = C_n^{n-k}$).

## 📝 2. Tam giác Pascal (Hệ số khai triển)
### ✅ Cấu trúc
- Hàng 0: 1
- Hàng 1: 1, 1
- Hàng 2: 1, 2, 1
- Hàng 3: 1, 3, 3, 1
- Hàng 4: 1, 4, 6, 4, 1
- Hàng 5: 1, 5, 10, 10, 5, 1
### ✅ Ý nghĩa
- Dùng để xác định nhanh các hệ số $C_n^k$ mà không cần dùng máy tính khi $n$ nhỏ.

## 🛠️ 3. Các dạng toán và Phương pháp giải
### 🔹 Dạng 1: Khai triển biểu thức cụ thể
- **Phương pháp:** Xác định đúng $a$, $b$ và $n$. Áp dụng công thức và rút gọn từng số hạng.
- **Lưu ý:** Nếu là $(a - b)^n$, hãy hiểu là $(a + (-b))^n$ để tránh sai dấu.
### 🔹 Dạng 2: Tìm hệ số của một số hạng trong khai triển
- **Phương pháp:** Viết dạng tổng quát của số hạng thứ $k+1$: $T_{k+1} = C_n^k a^{n-k} b^k$.
- Dựa vào yêu cầu đề bài (ví dụ tìm hệ số của $x^3$) để tìm $k$.
### 🔹 Dạng 3: Tính tổng các hệ số
- **Phương pháp:** Cho $x = 1$ (hoặc các giá trị thích hợp) vào biểu thức khai triển.
- **Ví dụ:** Tổng hệ số của $(2x + 1)^4$ là $f(1) = (2(1) + 1)^4 = 3^4 = 81$.

## 🌍 4. Ứng dụng thực tế
### ✅ Tài chính & Lãi suất
- Tính gần đúng giá trị tích lũy: $A = P(1 + r)^n$.
- Với $r$ rất nhỏ, $(1 + r)^n \approx 1 + nr$ (khai triển bậc thấp).
### ✅ Xác suất (Phân phối nhị thức)
- Tính xác suất để một biến cố xảy ra đúng $k$ lần trong $n$ phép thử độc lập.
### ✅ Vật lý & Kỹ thuật
- Tính toán sai số: Ước lượng độ biến thiên của đại lượng khi các biến số thay đổi nhỏ.
- Phân tích các mô hình đa biến trong kỹ thuật số.

## ⌨️ 5. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Tính tổ hợp $C_n^k$
- **Thao tác:** Nhập $n$ ⮕ `SHIFT` ⮕ `÷` ($nCr$) ⮕ Nhập $k$.
- Ví dụ $C_5^2$: `5` `SHIFT` `÷` `2` `=` (Kết quả: 10).
### ✅ Sử dụng TABLE để tìm hệ số (Menu 8)
- **Mục đích:** Tìm hệ số của $x^k$ khi khai triển $(Ax^p + B)^n$.
- **Thao tác:** Nhập $f(x) = C_n^x \cdot (A)^{n-x} \cdot (B)^x$.
- Thiết lập `Start: 0`, `End: n`, `Step: 1`.
- Tra bảng cột $f(x)$ để lấy hệ số tương ứng với vị trí $x$ (đóng vai trò là $k$).

## ⚠️ Lưu ý của Giáo viên
- Cẩn thận dấu âm: $(-b)^k$ sẽ dương nếu $k$ chẵn, âm nếu $k$ lẻ.
- Nhị thức Newton lớp 10 hiện nay tập trung chủ yếu vào $n = 4$ và $n = 5$.
