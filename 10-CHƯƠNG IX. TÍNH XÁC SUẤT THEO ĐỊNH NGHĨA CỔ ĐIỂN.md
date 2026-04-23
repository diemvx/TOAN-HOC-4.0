---
markmap:
  colorScheme: google
  math: katex
---

# 🎓 ÔN TẬP CHƯƠNG IX: TÍNH XÁC SUẤT THEO ĐỊNH NGHĨA CỔ ĐIỂN

## 1. 📘 Hệ thống kiến thức nền tảng
### ✅ Phép thử và Không gian mẫu
- **Phép thử ngẫu nhiên:** Một thí nghiệm mà kết quả không biết trước, nhưng tập hợp các kết quả có thể xảy ra là hoàn toàn xác định.
- **Không gian mẫu ($\Omega$):** Tập hợp tất cả các kết quả có thể có của phép thử.
- **Số phần tử không gian mẫu:** Ký hiệu $n(\Omega)$ hoặc $|\Omega|$.
### ✅ Biến cố và Xác suất
- **Biến cố ($A$):** Là tập con của không gian mẫu $\Omega$.
- **Định nghĩa cổ điển:** Xác suất của biến cố $A$ là $P(A) = \frac{n(A)}{n(\Omega)}$.
- **Tính chất:**
    - $0 \le P(A) \le 1$.
    - $P(\Omega) = 1; P(\varnothing) = 0$.
### ✅ Biến cố đối
- Biến cố đối của $A$ là $\overline{A} = \Omega \setminus A$ (biến cố "$A$ không xảy ra").
- **Công thức:** $P(\overline{A}) = 1 - P(A)$.

## 🛠️ 2. Các phương pháp tính số phần tử $n(A)$ và $n(\Omega)$
### 🔹 Phương pháp liệt kê
- Dùng cho không gian mẫu nhỏ (ví dụ: gieo 1 con xúc xắc, tung 2 đồng xu).
- Vẽ sơ đồ hình cây để tránh bỏ sót kết quả.
### 🔹 Sử dụng quy tắc đếm
- **Quy tắc cộng:** Khi công việc được thực hiện theo các phương án độc lập.
- **Quy tắc nhân:** Khi công việc trải qua nhiều giai đoạn liên tiếp.
### 🔹 Sử dụng Hoán vị - Chỉnh hợp - Tổ hợp
- **Hoán vị ($n!$):** Sắp xếp thứ tự $n$ phần tử.
- **Chỉnh hợp ($A_n^k$):** Chọn $k$ phần tử và có xếp thứ tự.
- **Tổ hợp ($C_n^k$):** Chọn $k$ phần tử và không xếp thứ tự (ví dụ: chọn nhóm, chọn tập con).

## 🧩 3. Các dạng toán trọng tâm
### 🔹 Dạng 1: Bài toán chọn vật/người
- **Phương pháp:** Thường dùng tổ hợp $C_n^k$ để tính $n(\Omega)$ và $n(A)$.
- **Ví dụ:** Chọn 3 học sinh từ 10 học sinh. $n(\Omega) = C_{10}^3$.
### 🔹 Dạng 2: Bài toán sắp xếp thứ tự
- **Phương pháp:** Dùng hoán vị hoặc chỉnh hợp.
- **Ví dụ:** Xếp 5 người vào một hàng dọc. $n(\Omega) = 5!$.
### 🔹 Dạng 3: Bài toán liên quan đến số tự nhiên
- **Phương pháp:** Gọi số cần tìm $\overline{a_1a_2...a_k}$, chọn từng chữ số theo điều kiện bài toán.
### 🔹 Dạng 4: Sử dụng biến cố đối (Tính ngược)
- **Dấu hiệu:** Có từ "ít nhất", "có tối đa", "không quá"...
- **Phương pháp:** Tính xác suất của trường hợp vi phạm yêu cầu, sau đó lấy $1$ trừ đi.

## 🌍 4. Ứng dụng thực tế
### ✅ Quản lý chất lượng sản phẩm
- Tính xác suất lấy ngẫu nhiên 2 phế phẩm từ một kiện hàng để đánh giá dây chuyền sản xuất.
### ✅ Trò chơi và Giải trí
- Xác định tỷ lệ thắng trong các trò chơi bốc thăm trúng thưởng hoặc chia bài.
### ✅ Y học và Thống kê
- Tính khả năng một mẫu thử có chứa kháng thể dựa trên tập hợp mẫu có sẵn.
### ✅ Giao thông
- Xác định xác suất các xe đi qua trạm thu phí vào một thời điểm cụ thể dựa trên tổ hợp biển số xe.

## ⌨️ 5. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Tính Tổ hợp và Chỉnh hợp
- **Tổ hợp ($nCr$):** `n` ⮕ `SHIFT` ⮕ `÷` ⮕ `k`.
- **Chỉnh hợp ($nPr$):** `n` ⮕ `SHIFT` ⮕ `x` ⮕ `k`.
### ✅ Tính xác suất trực tiếp bằng phân số
- Nhấn phím phân số $\frac{\square}{\square}$.
- Tử số: Nhập biểu thức tính $n(A)$.
- Mẫu số: Nhập biểu thức tính $n(\Omega)$.
- Nhấn `S⇔D` để đổi sang số thập phân (định dạng $0,abc$).
### ✅ Chức năng liệt kê số phần tử (Table)
- Với các bài toán tổng xúc xắc, dùng `Menu 8` (Table) để chạy hàm $f(x)$ đếm số cặp thỏa mãn.

## ⚠️ Lưu ý của Giáo viên
- Phân biệt rõ "chọn có hoàn lại" và "chọn không hoàn lại" (đối với lớp 10 thường là không hoàn lại).
- Luôn kiểm tra điều kiện $k \le n$ khi dùng $C_n^k, A_n^k$.
- Khi gặp bài toán có vectơ: Số vectơ tạo từ $n$ điểm là $A_n^2$ vì $\overrightarrow{AB}$ khác $\overrightarrow{BA}$, nhưng số đoạn thẳng là $C_n^2$.