---
markmap:
  colorScheme: default
  math: katex
---

# 📚 CHUYÊN ĐỀ TẬP HỢP (SETS)

## 1. 📘 Khái niệm cơ bản
### ✅ Định nghĩa và Ký hiệu
- Tập hợp là một khái niệm cơ bản của toán học.
- Ký hiệu: $a \in A$ (thuộc), $a \notin A$ (không thuộc).
- Cách cho tập hợp:
    - Liệt kê phần tử: $A = \{1; 2; 3\}$.
    - Chỉ ra tính chất đặc trưng: $A = \{x \in \mathbb{R} \mid P(x)\}$.
### ✅ Tập hợp con và Tập hợp bằng nhau
- **Tập con:** $A \subset B \Leftrightarrow (\forall x \in A \Rightarrow x \in B)$.
- **Bằng nhau:** $A = B \Leftrightarrow A \subset B$ và $B \subset A$.
- **Tập rỗng:** $\varnothing$ (không chứa phần tử nào). $\varnothing \subset A, \forall A$.
### ✅ Các tập hợp số thường gặp
- $\mathbb{N} \subset \mathbb{Z} \subset \mathbb{Q} \subset \mathbb{R}$.
- Các khoảng, đoạn: $[a; b], (a; b), [a; b), (a; b]$.

## 2. 📋 Các phép toán trên tập hợp
### 🔹 Phép giao ($A \cap B$)
- $A \cap B = \{x \mid x \in A \text{ và } x \in B\}$.
- Lấy phần chung của hai tập hợp.
### 🔹 Phép hợp ($A \cup B$)
- $A \cup B = \{x \mid x \in A \text{ hoặc } x \in B\}$.
- Gộp tất cả phần tử của hai tập hợp lại.
### 🔹 Phép hiệu ($A \setminus B$) và Phần bù ($C_A B$)
- $A \setminus B = \{x \mid x \in A \text{ và } x \notin B\}$.
- Phần bù: Nếu $B \subset A$ thì $C_A B = A \setminus B$.

## 3. 🧩 Các dạng toán và Phương pháp giải
### 🔹 Dạng 1: Xác định tập hợp
- **Phương pháp:** Giải phương trình hoặc bất phương trình của tính chất đặc trưng để liệt kê phần tử.
- **Ví dụ:** $A = \{x \in \mathbb{R} \mid x^2 - 3x + 2 = 0\} \Rightarrow A = \{1; 2\}$.
### 🔹 Dạng 2: Phép toán trên tập hợp số (Trục số)
- **Phương pháp:** - Vẽ các tập hợp trên trục số.
    - Dùng quy tắc "lấy phần chung" cho Giao, "tô đậm tất cả" cho Hợp.
### 🔹 Dạng 3: Bài toán thực tế (Biểu đồ Venn)
- **Công thức tính số phần tử:** $n(A \cup B) = n(A) + n(B) - n(A \cap B)$.

## 🌍 4. Ứng dụng thực tế
### ✅ Quản lý cơ sở dữ liệu
- Phép Giao/Hợp dùng để lọc dữ liệu khách hàng theo nhiều tiêu chí (SQL Joins).
### ✅ Thống kê dân số/Lớp học
- Phân loại học sinh giỏi Toán, giỏi Lý và tìm số học sinh giỏi cả hai môn.
- **Ví dụ:** Một lớp có 25 em thích bóng đá, 20 em thích bóng chuyền, 10 em thích cả hai. Hỏi lớp có bao nhiêu em thích ít nhất một môn?
### ✅ Quy hoạch vùng
- Xác định khu vực giao nhau giữa các quy hoạch đô thị hoặc vùng ảnh hưởng thiên tai.

## ⌨️ 5. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Hỗ trợ liệt kê phần tử (Table)
- **B1:** Vào `Menu 8` (Table).
- **B2:** Nhập biểu thức đặc trưng $f(x)$ (ví dụ: phương trình $x^2-3x+2$).
- **B3:** Thiết lập $Start, End, Step$ để kiểm tra các giá trị $x$ nào làm $f(x)=0$.
- **Ứng dụng:** Tìm các phần tử của tập hợp khi $x$ là số nguyên.
### ✅ Giải phương trình/Bất phương trình
- Sử dụng `Menu 9` để tìm nghiệm của các đa thức, từ đó xác định phần tử của tập hợp nhanh chóng.
### ✅ Kiểm tra số nguyên tố/Ước số
- Sử dụng phím `FACT` (phân tích thừa số nguyên tố) để xác định các phần tử trong các tập hợp liên quan đến tính chất chia hết.

## ⚠️ Lưu ý của Giáo viên
- Cẩn thận phân biệt giữa ký hiệu $\in$ (phần tử với tập hợp) và $\subset$ (tập hợp với tập hợp).
- Khi làm việc với các khoảng/đoạn trên trục số, chú ý ngoặc vuông $[ ]$ (lấy đầu mút) và ngoặc tròn $( )$ (không lấy đầu mút).
- Tập rỗng $\varnothing$ không được viết là $\{\varnothing\}$.
- Ký hiệu vectơ (nếu có bài toán liên quan): $\overrightarrow{AB}$ luôn dùng cho chuẩn chương trình mới.