# 📚 Ôn Thi Vào Lớp 10 – Toán Đại Số & Hình Học Nâng Cao

> 10 dạng bài quan trọng nhất, có lý thuyết và bài tập ví dụ có lời giải.

---

## 📐 ĐẠI SỐ NÂNG CAO

---

### Dạng 1: Phương Trình Bậc Hai – Hệ Thức Vi-ét & Ứng Dụng

#### 📖 Lý Thuyết

Cho phương trình bậc hai **ax² + bx + c = 0** (a ≠ 0) có hai nghiệm x₁, x₂. Hệ thức Vi-ét:

$$x_1 + x_2 = -\frac{b}{a} \qquad x_1 \cdot x_2 = \frac{c}{a}$$

**Ứng dụng thường gặp:**
- Tính x₁² + x₂² = (x₁+x₂)² - 2x₁x₂
- Tính x₁³ + x₂³ = (x₁+x₂)³ - 3x₁x₂(x₁+x₂)
- Tìm phương trình bậc hai khi biết nghiệm
- Điều kiện PT có nghiệm: **Δ = b² - 4ac ≥ 0**

#### ✏️ Bài Tập 1

Cho phương trình x² - 5x + 3 = 0 có hai nghiệm x₁, x₂. Không giải phương trình, hãy tính:

a) A = x₁² + x₂²  
b) B = x₁³ + x₂³  
c) C = (x₁ - x₂)²

<details>
<summary>💡 Xem lời giải</summary>

Theo Vi-ét: **x₁ + x₂ = 5**, **x₁·x₂ = 3**

- a) A = (x₁+x₂)² - 2x₁x₂ = 25 - 6 = **19**
- b) B = (x₁+x₂)³ - 3x₁x₂(x₁+x₂) = 125 - 45 = **80**
- c) C = (x₁+x₂)² - 4x₁x₂ = 25 - 12 = **13**

</details>

#### ✏️ Bài Tập 2 (Nâng cao)

Tìm m để phương trình x² - 2(m+1)x + m² - 3 = 0 có hai nghiệm dương phân biệt.

<details>
<summary>💡 Xem lời giải</summary>

Điều kiện có 2 nghiệm phân biệt: **Δ' > 0**

- Δ' = (m+1)² - (m²-3) = 2m + 4 > 0 → m > -2
- Hai nghiệm dương: x₁+x₂ = 2(m+1) > 0 → m > -1
- x₁·x₂ = m² - 3 > 0 → m < -√3 hoặc m > √3

Kết hợp: **m > √3 ≈ 1,73**

</details>

---

### Dạng 2: Hệ Phương Trình Hai Ẩn – Phương Pháp & Bài Toán Thực Tế

#### 📖 Lý Thuyết

Hệ phương trình bậc nhất hai ẩn có 3 phương pháp giải:

| Phương pháp | Khi nào dùng |
|-------------|--------------|
| **Thế** | Một ẩn dễ biểu diễn qua ẩn kia |
| **Cộng/trừ** | Hệ số của một ẩn bằng nhau hoặc đối nhau |
| **Đặt ẩn phụ** | PT phức tạp: 1/x, √x, ... |

#### ✏️ Bài Tập (Toán thực tế)

Hai vòi nước cùng chảy vào bể 12 giờ thì đầy. Nếu vòi 1 chảy 3 giờ rồi mở thêm vòi 2 thì sau 8 giờ nữa mới đầy. Hỏi mỗi vòi chảy một mình bao lâu thì đầy bể?

<details>
<summary>💡 Xem lời giải</summary>

Gọi thời gian vòi 1, vòi 2 chảy một mình là x, y (giờ).

- PT1: 1/x + 1/y = 1/12
- PT2: 3·(1/x) + 8·(1/x + 1/y) = 1 → 11/x + 8/y = 1

Đặt a = 1/x, b = 1/y:
- a + b = 1/12
- 11a + 8b = 1

Giải hệ: a = 1/20, b = 1/30

**Vòi 1: 20 giờ, Vòi 2: 30 giờ**

</details>

---

### Dạng 3: Bất Phương Trình & Hệ Bất Phương Trình

#### 📖 Lý Thuyết

- Nhân/chia cả hai vế với số âm → **đổi chiều** bất đẳng thức
- |ax + b| ≤ c ↔ -c ≤ ax+b ≤ c
- |ax + b| ≥ c ↔ ax+b ≤ -c hoặc ax+b ≥ c

#### ✏️ Bài Tập

Giải hệ bất phương trình:
```
{ 3x - 2 > 4
{ 2x + 1 ≤ 9
```

<details>
<summary>💡 Xem lời giải</summary>

- BPT 1: 3x > 6 → x > 2
- BPT 2: 2x ≤ 8 → x ≤ 4

Tập nghiệm: **2 < x ≤ 4**, hay x ∈ (2; 4]

</details>

#### ✏️ Bài Tập Nâng Cao

Tìm m để bất phương trình mx² - 2x + m ≥ 0 nghiệm đúng với mọi x ∈ ℝ.

<details>
<summary>💡 Xem lời giải</summary>

- Nếu m = 0: -2x ≥ 0 → sai với x > 0 → loại
- Nếu m ≠ 0: cần m > 0 và Δ' = 1 - m² ≤ 0
- 1 - m² ≤ 0 → m ≤ -1 hoặc m ≥ 1

Kết hợp m > 0: **m ≥ 1**

</details>

---

### Dạng 4: Hàm Số Bậc Hai – Đồ Thị & Tìm Giá Trị

#### 📖 Lý Thuyết

Hàm số **y = ax² + bx + c** (a ≠ 0) có đồ thị là parabol:

$$\text{Đỉnh: } I\!\left(-\frac{b}{2a};\, -\frac{\Delta}{4a}\right) \qquad \text{Trục đối xứng: } x = -\frac{b}{2a}$$

- **a > 0**: parabol mở lên → GTNN tại đỉnh
- **a < 0**: parabol mở xuống → GTLN tại đỉnh

#### ✏️ Bài Tập

Cho hàm số y = -x² + 4x + 1. Tìm tọa độ đỉnh, trục đối xứng và giá trị lớn nhất.

<details>
<summary>💡 Xem lời giải</summary>

a = -1, b = 4, c = 1

- x₀ = -4/(2·(-1)) = **2**
- y₀ = -4 + 8 + 1 = **5**

**Đỉnh I(2; 5)**, trục đối xứng **x = 2**

a < 0 → **GTLN = 5** tại x = 2

</details>

---

### Dạng 5: Căn Thức – Rút Gọn & Giải Phương Trình Vô Tỉ

#### 📖 Lý Thuyết

```
√(a²) = |a|          √a · √b = √(ab)
1/(√a+√b) = (√a-√b)/(a-b)     (trục căn thức mẫu)

⚠️ Lỗi sai phổ biến: √a + √b ≠ √(a+b)
```

#### ✏️ Bài Tập 1 – Rút gọn

Rút gọn: P = (√x + 1)/(√x - 1) - (√x - 1)/(√x + 1) - 4/(x-1) với x ≥ 0, x ≠ 1

<details>
<summary>💡 Xem lời giải</summary>

MTC = (√x - 1)(√x + 1) = x - 1

Tử = (√x+1)² - (√x-1)² - 4 = (x+2√x+1) - (x-2√x+1) - 4 = 4√x - 4

P = 4(√x-1)/(x-1) = **4/(√x+1)**

</details>

#### ✏️ Bài Tập 2 – PT vô tỉ

Giải phương trình: √(2x-3) + √(5-2x) = x² - 4x + 6

<details>
<summary>💡 Xem lời giải</summary>

ĐKXĐ: 3/2 ≤ x ≤ 5/2

**VT** ≤ √2·√((2x-3)+(5-2x)) = √2·√2 = 2 (BĐT Cauchy-Schwarz)

**VP** = (x-2)² + 2 ≥ 2

Đẳng thức khi VT = VP = 2: x = 2 thỏa mãn cả hai.

Nghiệm: **x = 2**

</details>

---

## 📏 HÌNH HỌC NÂNG CAO

---

### Dạng 1: Tam Giác Đồng Dạng & Hệ Quả

#### 📖 Lý Thuyết

Hai tam giác đồng dạng (△ABC ~ △A'B'C') khi:

| Trường hợp | Điều kiện |
|-----------|-----------|
| **c.c.c** | Ba cặp cạnh tỉ lệ |
| **c.g.c** | Hai cặp cạnh tỉ lệ, góc kẹp bằng nhau |
| **g.g** | Hai cặp góc bằng nhau |

$$\frac{AB}{A'B'} = \frac{BC}{B'C'} = \frac{CA}{C'A'} = k$$

**Hệ quả:** S△ABC / S△A'B'C' = k²

#### ✏️ Bài Tập

Tam giác ABC vuông tại A, đường cao AH. Biết BH = 4, HC = 9. Tính AH, AB, AC.

<details>
<summary>💡 Xem lời giải</summary>

- △ABH ~ △CAH (g.g): AH² = BH·HC = 36 → **AH = 6**
- AB² = BH·BC = 4·13 = 52 → **AB = 2√13**
- AC² = HC·BC = 9·13 = 117 → **AC = 3√13**

</details>

---

### Dạng 2: Đường Tròn – Góc Nội Tiếp & Góc Tạo Bởi Tiếp Tuyến

#### 📖 Lý Thuyết

- Góc nội tiếp = **½ cung bị chắn**
- Góc tâm = **cung bị chắn**
- Hai góc nội tiếp cùng chắn một cung → **bằng nhau**
- Góc nội tiếp chắn nửa đường tròn = **90°**
- Góc tạo bởi tiếp tuyến và dây = **½ cung bị chắn**

#### ✏️ Bài Tập

Cho đường tròn (O), AB là đường kính. C là điểm trên đường tròn. Tiếp tuyến tại C cắt đường thẳng AB tại D. Biết DA = 4, DB = 9. Tính bán kính.

<details>
<summary>💡 Xem lời giải</summary>

DC là tiếp tuyến → DC² = DA·DB = 4·9 = 36 → DC = 6

AB = DA + DB = 13 → **R = 13/2 = 6,5**

</details>

---

### Dạng 3: Tứ Giác Nội Tiếp & Tính Chất

#### 📖 Lý Thuyết

Tứ giác ABCD nội tiếp đường tròn **khi và chỉ khi**:

$$\angle A + \angle C = 180° \quad \text{và} \quad \angle B + \angle D = 180°$$

Dấu hiệu nhận biết:
- Hai góc đối bù nhau
- Bốn đỉnh cùng thuộc một đường tròn
- Hai đỉnh kề nhìn cạnh đối diện dưới cùng góc

#### ✏️ Bài Tập

Cho tam giác ABC, đường cao BD và CE cắt nhau tại H. F là giao điểm AH và BC. Chứng minh tứ giác BDHF nội tiếp.

<details>
<summary>💡 Xem lời giải</summary>

- ∠BDH = 90° (BD là đường cao)
- ∠BFH = 90° (AH ⊥ BC tại F)
- ∠BDH + ∠BFH = 180° → **BDHF nội tiếp** ∎

</details>

---

### Dạng 4: Diện Tích & Thể Tích Hình Không Gian

#### 📖 Lý Thuyết

| Hình | Diện tích xung quanh | Thể tích |
|------|---------------------|----------|
| **Hình trụ** | S = 2πRh | V = πR²h |
| **Hình nón** | S = πRl (l = √(R²+h²)) | V = ⅓πR²h |
| **Hình cầu** | S = 4πR² | V = 4/3·πR³ |

#### ✏️ Bài Tập

Một hình nón có đường kính đáy 12cm, đường sinh 10cm. Tính diện tích toàn phần và thể tích.

<details>
<summary>💡 Xem lời giải</summary>

R = 6cm, l = 10cm

h = √(l²-R²) = √(100-36) = **8cm**

- S_xq = π·6·10 = **60π cm²**
- S_tp = 60π + π·36 = **96π cm²**
- V = (1/3)π·36·8 = **96π cm³**

</details>

---

### Dạng 5: Chứng Minh Hình Học – Phương Pháp & Kỹ Thuật

#### 📖 Lý Thuyết

| Mục tiêu | Phương pháp |
|----------|-------------|
| Tam giác bằng nhau | c.c.c / c.g.c / g.c.g / g.g.c / cạnh huyền-góc nhọn |
| Tứ giác đặc biệt | Chứng minh đủ điều kiện định nghĩa |
| 3 điểm thẳng hàng | Chứng minh 2 đường thẳng trùng nhau |
| 4 điểm đồng viên | Chứng minh tứ giác nội tiếp |

#### ✏️ Bài Tập Tổng Hợp

Cho tam giác ABC nội tiếp đường tròn (O), AB = AC. M là trung điểm BC. Tiếp tuyến tại A cắt đường thẳng BC tại D. Chứng minh DA² = DB·DC.

<details>
<summary>💡 Xem lời giải</summary>

**Bước 1 – CM DA là tiếp tuyến:**

AB = AC, M là trung điểm BC → AM ⊥ BC → OM ⊥ BC (cùng ⊥ BC) → O, A, M thẳng hàng → OA ⊥ BC → DA ⊥ OA tại A → **DA là tiếp tuyến** ✓

**Bước 2 – CM DA² = DB·DC:**

△DAB ~ △DCA (g.g): DA/DB = DC/DA

→ **DA² = DB·DC** ∎

</details>

---

*📚 Chúc con học tốt và thi đỗ lớp 10! 🌟*
