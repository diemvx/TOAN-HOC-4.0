---
markmap:
  colorScheme: google
  math: katex
---

# 🎲 BIẾN CỐ VÀ XÁC SUẤT CỔ ĐIỂN (TOÁN 10)

## 1. 📘 Khái niệm cơ bản
### ✅ Phép thử và Không gian mẫu
- **Phép thử ngẫu nhiên:** Một hành động mà kết quả không đoán trước được nhưng biết tập hợp tất cả kết quả có thể.
- **Không gian mẫu ($\Omega$):** Tập hợp các kết quả có thể xảy ra của phép thử.
- **Số phần tử không gian mẫu:** Ký hiệu là $n(\Omega)$ hoặc $|\Omega|$.
### ✅ Biến cố ($A$)
- **Định nghĩa:** Là một tập con của không gian mẫu.
- **Biến cố không thể ($\varnothing$):** Không bao giờ xảy ra, $P(\varnothing) = 0$.
- **Biến cố chắc chắn ($\Omega$):** Luôn luôn xảy ra, $P(\Omega) = 1$.
- **Biến cố đối ($\overline{A}$):** "Không xảy ra biến cố $A$". Công thức: $P(\overline{A}) = 1 - P(A)$.

## 📐 2. Định nghĩa cổ điển của xác suất
### ✅ Công thức tính
- $P(A) = \frac{n(A)}{n(\Omega)}$
- Trong đó:
    - $n(A)$: Số kết quả thuận lợi cho biến cố $A$.
    - $n(\Omega)$: Tổng số kết quả có thể xảy ra.
### ✅ Điều kiện áp dụng
- Các kết quả của phép thử là đồng khả năng.
- Không gian mẫu có hữu hạn phần tử.
### ✅ Tính chất
- $0 \le P(A) \le 1$.

## 🛠️ 3. Phương pháp giải các dạng toán
### 🔹 Dạng 1: Xác định không gian mẫu và biến cố
- **Phương pháp:** Sử dụng quy tắc đếm (cộng, nhân) hoặc sơ đồ hình cây để liệt kê/tính số phần tử.
- **Ví dụ:** Gieo 2 con xúc xắc $\Rightarrow n(\Omega) = 6 \times 6 = 36$.
### 🔹 Dạng 2: Tính xác suất bằng định nghĩa
- **Bước 1:** Tính $n(\Omega)$.
- **Bước 2:** Tính $n(A)$ (thường dùng tổ hợp $C_n^k$, chỉnh hợp $A_n^k$, hoán vị $P_n$).
- **Bước 3:** Lập tỉ số $\frac{n(A)}{n(\Omega)}$.
### 🔹 Dạng 3: Sử dụng biến cố đối
- **Dấu hiệu:** Câu hỏi chứa từ "ít nhất", "có ít nhất một"...
- **Phương pháp:** Tính $P(\overline{A})$ sau đó lấy $1 - P(\overline{A})$.

## 🌍 4. Ứng dụng thực tế
### ✅ Trò chơi may rủi
- Tính xác suất trúng thưởng vé số, tung đồng xu trong thể thao.
- Tính khả năng rút được quân bài mong muốn trong bộ bài 52 lá.
### ✅ Kiểm tra chất lượng (KCS)
- Tính xác suất lấy được sản phẩm lỗi từ một lô hàng để quyết định nhập kho.
### ✅ Y sinh và Bảo hiểm
- Ước lượng khả năng xảy ra một loại bệnh dựa trên thống kê.
- Tính toán phí bảo hiểm dựa trên rủi ro xảy ra biến cố có hại.

## ⌨️ 5. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Tính số phần tử bằng Tổ hợp/Chỉnh hợp
- **Tổ hợp ($C_n^k$):** Nhấn `n` ⮕ `SHIFT` ⮕ `÷` ($nCr$) ⮕ `k`. (Dùng khi chọn nhóm không thứ tự).
- **Chỉnh hợp ($A_n^k$):** Nhấn `n` ⮕ `SHIFT` ⮕ `x` ($nPr$) ⮕ `k`. (Dùng khi chọn có thứ tự).
### ✅ Phép tính phân số xác suất
- Nhập trực tiếp biểu thức $\frac{n(A)}{n(\Omega)}$ bằng phím phân số.
- Nhấn `S⇔D` để chuyển đổi giữa phân số và số thập phân (ví dụ $0.25$ hoặc $25\%$).
### ✅ Chức năng liệt kê (Table - Menu 8)
- Sử dụng để liệt kê các trường hợp tổng của xúc xắc hoặc các phép thử đơn giản bằng hàm số.

## ⚠️ Lưu ý của Giáo viên
- Phân biệt kỹ khi nào dùng Quy tắc nhân (các bước liên tiếp) và Tổ hợp (chọn đồng thời).
- Xác suất của một biến cố không bao giờ lớn hơn $1$ hoặc nhỏ hơn $0$. Nếu tính ra kết quả ngoài khoảng này, hãy kiểm tra lại phép đếm.
- Vectơ xác suất: Trong các bài toán mở rộng, các kết quả của biến cố có thể biểu diễn qua một hệ tọa độ vectơ $\overrightarrow{v} = (P_1, P_2, \dots, P_n)$ với $\sum P_i = 1$.