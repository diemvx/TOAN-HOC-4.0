---
markmap:
  colorScheme: google
  math: katex
---

# 🔢 HOÁN VỊ - CHỈNH HỢP - TỔ HỢP

## 1. 📋 Hoán vị (Permutation)
### ✅ Định nghĩa
- Một hoán vị của tập hợp gồm $n$ phần tử là một cách sắp xếp **thứ tự** tất cả $n$ phần tử đó.
### ✅ Công thức
- $P_n = n! = n \cdot (n-1) \dots 2 \cdot 1$.
- Quy ước: $0! = 1$.
### ✅ Ví dụ
- Có bao nhiêu cách xếp 5 học sinh vào một ghế dài có 5 chỗ?
- Đáp số: $P_5 = 5! = 120$ cách.

## 2. 📋 Chỉnh hợp (Partial Permutation)
### ✅ Định nghĩa
- Lấy ra $k$ phần tử từ tập $n$ phần tử ($1 \le k \le n$) và **sắp xếp thứ tự** chúng.
### ✅ Công thức
- $A_n^k = \frac{n!}{(n-k)!}$.
### ✅ Ý nghĩa & Dấu hiệu
- Có chọn ra + Có sắp xếp thứ tự.
- Thường dùng cho: Ghi số điện thoại, lập số tự nhiên, trao chức vụ (Lớp trưởng, lớp phó).
### ✅ Ví dụ
- Từ 10 học sinh, chọn ra 2 bạn làm Lớp trưởng và Lớp phó.
- Đáp số: $A_{10}^2 = 90$ cách.

## 3. 📋 Tổ hợp (Combination)
### ✅ Định nghĩa
- Lấy ra $k$ phần tử từ tập $n$ phần tử ($0 \le k \le n$) mà **không quan tâm thứ tự**.
### ✅ Công thức
- $C_n^k = \frac{n!}{k!(n-k)!}$.
- Tính chất: $C_n^k = C_n^{n-k}$.
### ✅ Ý nghĩa & Dấu hiệu
- Chỉ chọn ra + Không quan tâm thứ tự.
- Thường dùng cho: Chọn nhóm đi trực nhật, chọn tập con, chọn quân bài.
### ✅ Ví dụ
- Từ 10 học sinh, chọn ra một nhóm 2 bạn đi lao động.
- Đáp số: $C_{10}^2 = 45$ cách.

## 🧩 4. Phân biệt & Phương pháp giải
### 🔹 Bảng phân biệt nhanh
- **Hoán vị:** Dùng hết $n$ phần tử, có thứ tự.
- **Chỉnh hợp:** Lấy $k$ trong $n$ phần tử, có thứ tự.
- **Tổ hợp:** Lấy $k$ trong $n$ phần tử, không thứ tự.
### 🔹 Các dạng toán thường gặp
- **Dạng 1: Bài toán đếm số tự nhiên:** Sử dụng Chỉnh hợp (nếu các chữ số khác nhau) hoặc Quy tắc nhân.
- **Dạng 2: Sắp xếp người và đồ vật:** Dùng Hoán vị hoặc Chỉnh hợp. <BR>Chú ý các điều kiện "đứng cạnh nhau" (dùng phương pháp buộc) hoặc "không đứng cạnh nhau" (dùng phương pháp vách ngăn).
- **Dạng 3: Bài toán chọn nhóm/tổ:** Dùng Tổ hợp.
- **Dạng 4: Hình học:** Chọn $k$ điểm để tạo thành tam giác ($C_n^3$), đoạn thẳng ($C_n^2$), giao điểm.

## 🌍 5. Ứng dụng thực tế
### ✅ Quản lý và Tổ chức
- Sắp xếp lịch thi đấu vòng tròn cho các đội bóng ($C_n^2$).
- Phân công công việc trong dự án sao cho mỗi người giữ một vai trò khác nhau ($A_n^k$).
### ✅ Công nghệ & An ninh
- Tính tổng số mật mã có thể có của một loại khóa số để đánh giá độ bảo mật.
### ✅ Sinh học & Y tế
- Tính toán số lượng các tổ hợp gen hoặc các cách kết hợp thuốc trong thí nghiệm y khoa.

## ⌨️ 6. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Tính Giai thừa ($n!$)
- Nhập số $n$ ⮕ Nhấn `SHIFT` ⮕ `x⁻¹` (phím có chữ $x!$).
### ✅ Tính Chỉnh hợp ($A_n^k$) - Lệnh $nPr$
- Nhập $n$ ⮕ Nhấn `SHIFT` ⮕ `x` (dấu nhân, phía trên có chữ $nPr$) ⮕ Nhập $k$ ⮕ `=`.
### ✅ Tính Tổ hợp ($C_n^k$) - Lệnh $nCr$
- Nhập $n$ ⮕ Nhấn `SHIFT` ⮕ `÷` (dấu chia, phía trên có chữ $nCr$) ⮕ Nhập $k$ ⮕ `=`.

## ⚠️ Lưu ý của Giáo viên
- Phải xác định rõ bài toán **có thứ tự** hay **không có thứ tự** trước khi đặt bút giải.
- Nhớ điều kiện của $n$ và $k$: $n, k \in \mathbb{N}$ và $k \le n$.
- Đối với bài toán đếm số tự nhiên, chữ số đầu tiên ($a_1$) luôn phải khác $0$.
