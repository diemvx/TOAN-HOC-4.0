---
markmap:
  colorScheme: google
  math: katex
---

# 🎓 ÔN TẬP CHƯƠNG VIII: ĐẠI SỐ TỔ HỢP (TOÁN 10)

## 1. 📂 Quy tắc đếm cơ bản
### ✅ Quy tắc cộng
- **Định nghĩa:** Một công việc được thực hiện bởi một trong hai phương án độc lập. Phương án $A$ có $m$ cách, phương án $B$ có $n$ cách.
- **Công thức:** Tổng số cách là $m + n$.
- **Dấu hiệu:** Các phương án tách biệt, thực hiện xong một phương án là xong công việc.
### ✅ Quy tắc nhân
- **Định nghĩa:** Một công việc bao gồm hai công đoạn liên tiếp. Công đoạn 1 có $m$ cách, công đoạn 2 có $n$ cách.
- **Công thức:** Tổng số cách là $m \times n$.
- **Dấu hiệu:** Phải thực hiện tất cả các công đoạn mới xong công việc.

## 2. 📂 Hoán vị - Chỉnh hợp - Tổ hợp
### ✅ Hoán vị (Permutation)
- **Định nghĩa:** Sắp xếp thứ tự **tất cả** $n$ phần tử của một tập hợp.
- **Công thức:** $P_n = n! = n(n-1)...2.1$.
- **Ví dụ:** Xếp 6 học sinh vào 6 ghế hàng ngang: $P_6 = 720$.
### ✅ Chỉnh hợp (Arrangement)
- **Định nghĩa:** Chọn $k$ phần tử từ $n$ phần tử và **có sắp xếp thứ tự**.
- **Công thức:** $A_n^k = \frac{n!}{(n-k)!}$ ($1 \le k \le n$).
- **Dấu hiệu:** Chọn + Xếp thứ tự (ví dụ: bầu chức vụ, lập số tự nhiên).
### ✅ Tổ hợp (Combination)
- **Định nghĩa:** Chọn $k$ phần tử từ $n$ phần tử và **không quan tâm thứ tự**.
- **Công thức:** $C_n^k = \frac{n!}{k!(n-k)!}$ ($0 \le k \le n$).
- **Dấu hiệu:** Chỉ chọn nhóm, chọn tập con.

## 3. 📂 Nhị thức Newton
### ✅ Công thức khai triển (với $n \le 5$)
- **Tổng quát:** $(a + b)^n = \sum_{k=0}^{n} C_n^k a^{n-k} b^k$.
- **Khai triển $(a+b)^4$:** $C_4^0 a^4 + C_4^1 a^3b + C_4^2 a^2b^2 + C_4^3 ab^3 + C_4^4 b^4$.
- **Khai triển $(a+b)^5$:** $C_5^0 a^5 + C_5^1 a^4b + C_5^2 a^3b^2 + C_5^3 a^2b^3 + C_5^4 ab^4 + C_5^5 b^5$.
### ✅ Đặc điểm
- Số số hạng là $n + 1$.
- Tổng số mũ của $a$ và $b$ trong mỗi số hạng luôn bằng $n$.
- Các hệ số đối xứng qua số hạng chính giữa: $C_n^k = C_n^{n-k}$.

## 🛠️ 4. Các dạng toán trọng tâm
### 🔹 Dạng 1: Bài toán đếm số tự nhiên
- **Phương pháp:** Gọi số cần tìm $\overline{a_1a_2...a_k}$. Chọn từng chữ số (chú ý $a_1 \neq 0$).
- Sử dụng quy tắc nhân hoặc chỉnh hợp $A_n^k$ khi các chữ số khác nhau.
### 🔹 Dạng 2: Bài toán sắp xếp và chọn nhóm
- **Phương pháp:** Phân biệt rõ có thứ tự (Chỉnh hợp) hay không (Tổ hợp).
- **Ví dụ:** Chọn 2 người trong 10 người đi trực nhật dùng $C_{10}^2$.
### 🔹 Dạng 3: Bài toán liên quan đến hình học
- **Số đoạn thẳng/vectơ:** Chọn 2 điểm trong $n$ điểm. Đoạn thẳng: $C_n^2$; Vectơ: $A_n^2$ (vì $\overrightarrow{AB} \neq \overrightarrow{BA}$).
- **Số tam giác:** Chọn 3 điểm không thẳng hàng: $C_n^3$.
### 🔹 Dạng 4: Tìm hệ số trong khai triển Nhị thức Newton
- **Phương pháp:** Viết số hạng tổng quát và tìm $k$ dựa trên yêu cầu về số mũ.

## 🌍 5. Ứng dụng thực tế
### ✅ Quản lý và An ninh
- Tính tổng số mật mã (PIN) có thể có cho điện thoại hoặc thẻ ngân hàng.
- Thiết lập sơ đồ biển số xe để không bị trùng lặp.
### ✅ Thể thao & Tổ chức
- Tính số trận đấu trong một giải bóng đá vòng tròn một lượt ($C_n^2$).
- Cách phân công công việc cho các phòng ban.
### ✅ Tin học
- Thuật toán tìm đường đi, tối ưu hóa sự kết hợp trong lập trình.

## ⌨️ 6. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Các phím chức năng
- **Giai thừa ($n!$):** Nhấn `x!` (thường là `SHIFT` + `x⁻¹`).
- **Chỉnh hợp ($A_n^k$):** Nhấn `n` ⮕ `SHIFT` ⮕ `x` (phím $nPr$) ⮕ `k`.
- **Tổ hợp ($C_n^k$):** Nhấn `n` ⮕ `SHIFT` ⮕ `÷` (phím $nCr$) ⮕ `k`.
### ✅ Tính nhanh hệ số Nhị thức (Menu 8 - Table)
- Nhập hàm $f(x) = C_n^x \cdot a^{n-x} \cdot b^x$.
- Thiết lập `Start: 0`, `End: n`, `Step: 1`.
- Cột $f(x)$ sẽ hiển thị toàn bộ hệ số của khai triển.

## ⚠️ Lưu ý của Giáo viên
- Cần phân biệt kỹ **Quy tắc cộng** (phương án hoàn thành việc) và **Quy tắc nhân** (công đoạn chưa hoàn thành việc).
- Đối với Chỉnh hợp và Tổ hợp: Hãy đặt câu hỏi "Thay đổi thứ tự có tạo ra kết quả mới không?". Nếu có ⮕ Chỉnh hợp; Nếu không ⮕ Tổ hợp.
- Khi làm bài Nhị thức Newton có dấu trừ $(a - b)^n$, hãy coi là $(a + (-b))^n$ để tránh nhầm hệ số.