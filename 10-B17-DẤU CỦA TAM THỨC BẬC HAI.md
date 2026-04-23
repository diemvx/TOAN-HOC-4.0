---
markmap:
  colorScheme: google
  math: katex
---

# 📐 DẤU CỦA TAM THỨC BẬC HAI (TOÁN 10)

## 1. 📂 Định nghĩa và Định lý về dấu
### ✅ Tam thức bậc hai
- Dạng: $f(x) = ax^2 + bx + c$ ($a \neq 0$).
- Biệt thức: $\Delta = b^2 - 4ac$ (hoặc $\Delta' = b'^2 - ac$).
### ✅ Định lý về dấu của tam thức bậc hai
- **Trường hợp $\Delta < 0$:** $f(x)$ luôn cùng dấu với hệ số $a$ với mọi $x \in \mathbb{R}$.
- **Trường hợp $\Delta = 0$:** $f(x)$ luôn cùng dấu với hệ số $a$ với mọi $x \neq -\frac{b}{2a}$.
- **Trường hợp $\Delta > 0$:** $f(x)$ có hai nghiệm phân biệt $x_1, x_2$ ($x_1 < x_2$).
    - Trong khoảng nghiệm $(x_1; x_2)$: $f(x)$ trái dấu với hệ số $a$.
    - Ngoài khoảng nghiệm $(-\infty; x_1) \cup (x_2; +\infty)$: $f(x)$ cùng dấu với hệ số $a$.
    - *Mẹo nhớ:* "Trong trái, ngoài cùng".

## 🛠️ 2. Các dạng toán và Phương pháp giải
### 🔹 Dạng 1: Xét dấu tam thức bậc hai
- **Bước 1:** Tìm nghiệm của $f(x) = 0$.
- **Bước 2:** Xác định dấu của hệ số $a$.
- **Bước 3:** Lập bảng xét dấu và kết luận.
### 🔹 Dạng 2: Giải bất phương trình (BPT) bậc hai
- $ax^2 + bx + c > 0$ (hoặc $<, \ge, \le 0$).
- **Phương pháp:** Tìm nghiệm của tam thức rồi áp dụng định lý về dấu để lấy khoảng nghiệm phù hợp với chiều của BPT.
### 🔹 Dạng 3: Tìm tham số $m$ để biểu thức luôn dương/âm
- $ax^2 + bx + c > 0, \forall x \in \mathbb{R} \Leftrightarrow \begin{cases} a > 0 \\ \Delta < 0 \end{cases}$.
- $ax^2 + bx + c < 0, \forall x \in \mathbb{R} \Leftrightarrow \begin{cases} a < 0 \\ \Delta < 0 \end{cases}$.
- *Lưu ý:* Nếu hệ số $a$ chứa tham số, phải xét trường hợp $a = 0$ riêng.

## 🌍 3. Ứng dụng thực tế
### ✅ Kinh doanh và Kinh tế
- **Xác định khoảng lợi nhuận:** Giải BPT $L(x) > 0$ để tìm số lượng sản phẩm cần bán để cửa hàng có lãi.
- **Tối ưu chi phí:** Tìm khoảng giá trị để chi phí sản xuất không vượt quá ngân sách cho phép.
### ✅ Vật lý và Kỹ thuật
- **Tầm bay của vật ném:** Xác định khoảng thời gian $t$ mà độ cao của vật $h(t) > 0$ (vật đang ở trên mặt đất).
- **Thiết kế cầu đường:** Tính toán khoảng cách an toàn dựa trên các cung đường có dạng Parabol.
### ✅ Đời sống
- Dự đoán khoảng thời gian an toàn cho các sự kiện dựa trên mô hình hàm số bậc hai (nhiệt độ, lưu lượng nước).

## ⌨️ 4. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Giải Bất phương trình (Menu A)
- **Thao tác (580VNX):** `Menu` $\rightarrow$ `A` (Bất phương trình).
- **Chọn bậc:** Chọn `2` (Bậc hai).
- **Chọn dạng:** Chọn dạng tương ứng ($>, <, \ge, \le$).
- **Nhập hệ số:** Nhập $a, b, c$ và nhấn `=`.
- **Kết quả:** Máy sẽ hiển thị trực tiếp tập nghiệm của BPT.
### ✅ Kiểm tra dấu tại một điểm (Menu 1)
- Nhập biểu thức $ax^2 + bx + c$.
- Nhấn phím `CALC`, nhập giá trị $x$ bất kỳ trong khoảng cần xét.
- Kết quả hiện số âm hay dương chính là dấu của tam thức trong khoảng đó.

## ⚠️ Lưu ý của Giáo viên
- Phải luôn chú ý dấu của hệ số $a$ trước khi xét dấu.
- Trong BPT chứa dấu bằng ($\ge, \le$), tập nghiệm phải bao gồm cả các nghiệm $x_1, x_2$ (dùng ngoặc vuông $[\dots]$).
- Nếu $\Delta < 0$ và $a > 0$, thì $ax^2 + bx + c > 0$ có tập nghiệm $S = \mathbb{R}$.
- Khi gặp bài toán có vectơ dịch chuyển $\overrightarrow{u}(p;q)$ tác động vào tam thức, hãy xác định lại hàm số mới trước khi xét dấu.