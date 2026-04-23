---
markmap:
  colorScheme: default
  math: katex
---

# 🎲 TÍNH XÁC SUẤT THEO ĐỊNH NGHĨA CỔ ĐIỂN<br>(LỚP 10)

## 1. 📂 Các khái niệm nền tảng
### ✅ Phép thử ngẫu nhiên
- **Định nghĩa:** Là hành động mà kết quả không dự đoán trước được, <BR> nhưng tập hợp các kết quả có thể xảy ra đã biết rõ.
- **Ký hiệu:** $T$.
### ✅ Không gian mẫu ($\Omega$)
- **Ý nghĩa:** Tập hợp tất cả các kết quả có thể xảy ra của phép thử.
- **Số phần tử không gian mẫu:** $n(\Omega)$ hoặc $|\Omega|$.
### ✅ Biến cố ($A$)
- **Định nghĩa:** Là một tập con của không gian mẫu.
- **Biến cố không thể:** $\varnothing$ ($P(\varnothing) = 0$).
- **Biến cố chắc chắn:** $\Omega$ ($P(\Omega) = 1$).
- **Số kết quả thuận lợi cho $A$:** $n(A)$ hoặc $|A|$.

## 2. 📏 Công thức tính xác suất cổ điển
### ✅ Công thức chính
- $P(A) = \frac{n(A)}{n(\Omega)}$
- **Điều kiện:** Các kết quả của phép thử phải có đồng khả năng xảy ra.
### ✅ Tính chất
- $0 \le P(A) \le 1$.
- **Biến cố đối ($\overline{A}$):** $P(\overline{A}) = 1 - P(A)$. (Dùng khi tính trực tiếp $A$ quá phức tạp).
### 📝 Ví dụ
- Gieo một con súc sắc cân đối. Tính xác suất xuất hiện mặt chẵn.
- $\Omega = \{1; 2; 3; 4; 5; 6\} \Rightarrow n(\Omega) = 6$.
- $A = \{2; 4; 6\} \Rightarrow n(A) = 3$.
- $P(A) = \frac{3}{6} = 0,5$.

## 3. 🧩 Phương pháp giải các dạng toán
### 🔹 Dạng 1: Liệt kê phần tử
- Áp dụng cho các bài toán có không gian mẫu nhỏ (gieo súc sắc, đồng xu).
- Liệt kê tập $\Omega$ và tập $A$ để đếm số phần tử.
### 🔹 Dạng 2: Sử dụng quy tắc đếm <BR>(Hoán vị, Chỉnh hợp, Tổ hợp)
- Áp dụng cho bài toán chọn vật, chọn người, sắp xếp số.
- **Bước 1:** Tính $n(\Omega)$ bằng tổ hợp hoặc quy tắc nhân.
- **Bước 2:** Tính $n(A)$ thỏa mãn điều kiện đề bài.
- **Bước 3:** Lập tỉ số.
### 🔹 Dạng 3: Sử dụng biến cố đối
- Dấu hiệu: Đề bài có cụm từ "ít nhất", "có tối đa",...
- Tính $P(\overline{A})$ sau đó lấy $1 - P(\overline{A})$.

## 🌍 4. Ứng dụng thực tế
### ✅ Trò chơi may rủi
- Tính xác suất trúng thưởng vé số, tung đồng xu quyết định đội giao bóng trong bóng đá.
### ✅ Quản trị rủi ro & Bảo hiểm
- Dự đoán tỉ lệ sản phẩm lỗi trong một lô hàng để đưa ra chính sách bảo hành.
### ✅ Kiểm tra y tế
- Tính xác suất một người mắc bệnh dựa trên tỉ lệ dương tính giả của xét nghiệm.
### ✅ Di truyền học
- Dự đoán xác suất đời con mang kiểu hình nhất định từ kiểu gen của bố mẹ.

## ⌨️ 5. Hướng dẫn Máy tính cầm tay <br>(Casio 580VNX / 880BTG)
### ✅ Tính số phần tử bằng Chỉnh hợp/Tổ hợp
- **Tổ hợp ($C_n^k$):** Nhập $n \rightarrow$ `SHIFT` $\rightarrow$ `÷` ($\text{nCr}$) $\rightarrow$ Nhập $k$.
- **Chỉnh hợp ($A_n^k$):** Nhập $n \rightarrow$ `SHIFT` $\rightarrow$ `x` ($\text{nPr}$) $\rightarrow$ Nhập $k$.
### ✅ Tính trực tiếp xác suất
- Nhập phân số: $\frac{\text{Cách chọn thuận lợi}}{\text{Tổng cách chọn}}$.
- **Ví dụ:** Chọn 3 học sinh từ 10 học sinh để có 2 nam (biết lớp có 6 nam, 4 nữ).
- Nhập: $\frac{6 \text{C} 2 \times 4 \text{C} 1}{10 \text{C} 3}$ rồi nhấn `=`.
### ✅ Chuyển đổi kết quả
- Nhấn phím `S⇔D` để chuyển từ phân số sang số thập phân <br>(ví dụ $1/2 \to 0,5$) để dễ nhận xét độ lớn xác suất.

## ⚠️ Lưu ý của Giáo viên
- Luôn xác định rõ phép thử là gì để không tính sai $n(\Omega)$.
- Phân biệt chọn "có thứ tự" (Chỉnh hợp) và "không thứ tự" (Tổ hợp).
- Xác suất luôn nằm trong đoạn $[0; 1]$, nếu tính ra kết quả ngoài đoạn này chắc chắn đã làm sai.
- Với các bài toán đếm vectơ: $\overrightarrow{AB}$ khác $\overrightarrow{BA}$ nên phải dùng $A_n^2$ thay vì $C_n^2$.