---
markmap:
  colorScheme: google
  math: katex
---

# 🔢 QUY TẮC ĐẾM (TOÁN 10)

## 1. ➕ Quy tắc cộng (Addition Rule)
### ✅ Công thức & Định nghĩa
- Giả sử một công việc có thể thực hiện theo một trong hai phương án:
  - Phương án $A$ có $n$ cách thực hiện.
  - Phương án $B$ có $m$ cách thực hiện.
  - Các cách thực hiện của hai phương án không trùng nhau.
- **Tổng số cách:** $n + m$.
### ✅ Ý nghĩa
- Dùng khi các phương án độc lập với nhau, thực hiện phương án này thì không thực hiện phương án kia (Dấu hiệu: từ "hoặc").
### ✅ Ví dụ
- Một quán có 5 loại nước ngọt và 4 loại trà sữa. Để chọn 1 loại đồ uống, ta có: $5 + 4 = 9$ cách.

## 2. ✖️ Quy tắc nhân (Multiplication Rule)
### ✅ Công thức & Định nghĩa
- Giả sử một công việc bao gồm hai công đoạn liên tiếp:
  - Công đoạn 1 có $n$ cách thực hiện.
  - Với mỗi cách thực hiện công đoạn 1, có $m$ cách thực hiện công đoạn 2.
- **Tổng số cách:** $n \times m$.
### ✅ Ý nghĩa
- Dùng khi công việc bắt buộc phải trải qua nhiều bước nối tiếp nhau mới hoàn thành (Dấu hiệu: từ "và", "liên tiếp").
### ✅ Ví dụ
- Bạn có 3 cái áo và 2 cái quần. Để chọn một bộ quần áo, ta có: $3 \times 2 = 6$ cách.

## 🛠️ 3. Phương pháp giải các dạng toán đếm
### 🔹 Dạng 1: Bài toán đếm số tự nhiên
- **Phương pháp:** Gọi số cần tìm có dạng $\overline{a_1a_2...a_k}$.
- Chọn từng chữ số dựa trên điều kiện bài toán (khác nhau, chẵn/lẻ, chia hết cho 5...).
- Áp dụng quy tắc nhân.
### 🔹 Dạng 2: Bài toán đếm sơ đồ hình cây
- **Phương pháp:** Vẽ các nhánh tượng trưng cho các lựa chọn tại mỗi công đoạn.
- Phù hợp cho các bài toán có ít lựa chọn nhưng điều kiện ràng buộc phức tạp.
### 🔹 Dạng 3: Bài toán đếm có điều kiện "không quá" hoặc "ít nhất"
- **Phương pháp 1:** Chia các trường hợp (dùng Quy tắc cộng).
- **Phương pháp 2 (Phần bù):** Tổng số cách trừ đi số cách không thỏa mãn yêu cầu.

## 🌍 4. Ứng dụng thực tế
### ✅ Công nghệ thông tin
- Tính số lượng mật khẩu có thể tạo ra với độ dài $k$ ký tự.
- Mã hóa dữ liệu, biển số xe, mã vạch sản phẩm.
### ✅ Đời sống & Kinh doanh
- Thiết kế thực đơn (Combo): Chọn 1 món chính, 1 món phụ và 1 đồ uống.
- Sắp xếp lịch thi đấu, phân công ca trực trong công ty.
### ✅ Di truyền học
- Đếm số kiểu gen, kiểu hình có thể xảy ra trong các phép lai.

## ⌨️ 5. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Tính toán dãy tính (Quy tắc nhân/cộng)
- Nhập trực tiếp các phép tính cộng hoặc nhân các kết quả thành phần.
- **Ví dụ:** $5 \times 4 \times 3$ hoặc $2 + 5 + 7$.
### ✅ Phép tính Giai thừa (Factorial)
- Dùng khi đếm số cách sắp xếp $n$ phần tử ($n!$).
- **Thao tác:** Nhập $n$ ⮕ `SHIFT` ⮕ `x⁻¹` ($x!$).
### ✅ Phép tính Chỉnh hợp & Tổ hợp (Liên quan quy tắc nhân)
- Chỉnh hợp ($A_n^k$): `n` ⮕ `SHIFT` ⮕ `x` ($nPr$) ⮕ `k`.
- Tổ hợp ($C_n^k$): `n` ⮕ `SHIFT` ⮕ `÷` ($nCr$) ⮕ `k`.

## ⚠️ Lưu ý của Giáo viên
- **Phân biệt:** Nếu xong một bước mà công việc đã hoàn thành ⮕ **Quy tắc cộng**. Nếu xong một bước mà công việc vẫn chưa xong ⮕ **Quy tắc nhân**.
- Chú ý điều kiện các chữ số phải khác nhau ($\neq$) và chữ số hàng cao nhất (đầu tiên) phải khác $0$.
- Luôn kiểm tra xem các trường hợp có bị đếm lặp (trùng) hay không.