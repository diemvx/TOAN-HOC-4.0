---
markmap:
  colorScheme: default
  math: katex
---

# 📉 BÀI 14. CÁC SỐ ĐẶC TRƯNG ĐO ĐỘ PHÂN TÁN (TOÁN 10)

## 1. 📏 Khoảng biến thiên ($R$) và Khoảng tứ phân vị ($\Delta_Q$)
### ✅ Khoảng biến thiên ($R$)
- **Công thức:** $R = x_{max} - x_{min}$.
- **Ý nghĩa:** Đo độ xòe của dữ liệu từ giá trị nhỏ nhất đến giá trị lớn nhất.
- **Hạn chế:** Bị ảnh hưởng rất lớn bởi các giá trị ngoại lệ (giá trị quá lớn hoặc quá nhỏ).
### ✅ Khoảng tứ phân vị ($\Delta_Q$)
- **Công thức:** $\Delta_Q = Q_3 - Q_1$.
- **Ý nghĩa:** Đo độ phân tán của 50% số liệu ở chính giữa mẫu số liệu.
- **Ưu điểm:** Không bị ảnh hưởng bởi các giá trị ngoại lệ.

## 2. 📊 Phương sai ($s^2$) và Độ lệch chuẩn ($s$)
### ✅ Phương sai ($s^2$)
- **Công thức (mẫu số liệu $n$ phần tử):** $s^2 = \frac{1}{n} \sum_{i=1}^{n} (x_i - \bar{x})^2$.
- **Công thức (mẫu có tần số):** $s^2 = \frac{n_1(x_1 - \bar{x})^2 + \dots + n_k(x_k - \bar{x})^2}{n}$.
- **Ý nghĩa:** Trung bình bình phương khoảng cách từ mỗi số liệu đến số trung bình.
### ✅ Độ lệch chuẩn ($s$)
- **Công thức:** $s = \sqrt{s^2}$.
- **Ý nghĩa:** Có cùng đơn vị với mẫu số liệu. $s$ càng lớn thì số liệu càng phân tán (không đồng đều),<BR> $s$ càng nhỏ thì số liệu càng tập trung quanh số trung bình (đồng đều).

## 🧩 3. Phương pháp giải & Giá trị ngoại lệ
### 🔹 So sánh độ ổn định
- So sánh hai mẫu số liệu $A$ và $B$. Mẫu nào có $s^2$ hoặc $s$ nhỏ hơn thì mẫu đó ổn định/đồng đều hơn.
### 🔹 Xác định giá trị ngoại lệ (Outliers)
- Một giá trị $x$ được coi là ngoại lệ nếu:
  - $x > Q_3 + 1,5 \Delta_Q$
  - hoặc $x < Q_1 - 1,5 \Delta_Q$
- **Ứng dụng:** Loại bỏ các dữ liệu sai lệch do đo đạc hoặc ghi chép.

## 🌍 4. Ứng dụng thực tế
### ✅ Trong Nông nghiệp
- So sánh năng suất của hai giống lúa. Giống lúa có độ lệch chuẩn nhỏ hơn sẽ cho năng suất ổn định hơn qua các mùa vụ.
### ✅ Trong Sản xuất & Công nghiệp
- Kiểm soát chất lượng sản phẩm (đường kính bu lông, khối lượng tịnh). Độ lệch chuẩn thấp chứng tỏ dây chuyền sản xuất có độ chính xác cao.
### ✅ Trong Tài chính & Chứng khoán
- Độ lệch chuẩn của tỷ suất sinh lời được dùng để đo lường **rủi ro** của danh mục đầu tư. $s$ càng cao, rủi ro càng lớn.

## ⌨️ 5. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Cài đặt Thống kê (Menu 6)
- **Bước 1:** `Menu` ⮕ `6` (Statistics) ⮕ `1` (1-Variable).
- **Bước 2 (Bật tần số):** `Shift` ⮕ `Menu` ⮕ `Mũi tên xuống` ⮕ `Statistics` ⮕ `On`.
### ✅ Nhập và Xuất dữ liệu
- Nhập giá trị vào cột $X$ và tần số vào cột $Freq$.
- Nhấn `AC` sau khi nhập xong.
- Nhấn `OPTN` ⮕ `2` (1-Variable Calc).
### ✅ Đọc ký hiệu trên màn hình
- $\bar{x}$: Số trung bình.
- $\sigma^2 x$: Phương sai của quần thể (thường dùng $s^2$ trong SGK là $sx^2$).
- $\sigma x$: Độ lệch chuẩn (thường dùng $s$ trong SGK là $sx$).
- $Q_1, Q_3$: Tứ phân vị (dùng để tính $\Delta_Q$).

## ⚠️ Lưu ý của Giáo viên
- **Lỗi thường gặp:** Quên không lấy căn bậc hai của phương sai khi đề bài yêu cầu tìm độ lệch chuẩn.
- **Tư duy:** Khoảng biến thiên chỉ dùng cho dữ liệu thô, sơ bộ; Phương sai và Độ lệch chuẩn mới là "thước đo" tinh tế cho sự ổn định.
- **Ký hiệu:** Trong các tính toán phức tạp liên quan đến Vectơ tọa độ dữ liệu $\overrightarrow{x} = (x_1, x_2, \dots, x_n)$, độ lệch chuẩn liên quan mật thiết đến độ dài của vectơ hiệu $(\overrightarrow{x} - \overrightarrow{\bar{x}})$.