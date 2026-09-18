# Dự Án: Cấp Số Cộng, Cấp Số Nhân Và Ứng Dụng Trong Tài Chính

Đây là dự án nghiên cứu và vận dụng **cấp số cộng** và **cấp số nhân** vào các bài toán thực tế trong lĩnh vực tài chính. Dự án tập trung trình bày khái niệm, công thức, tính chất của hai loại cấp số; đồng thời minh họa cách sử dụng chúng trong các bài toán về **lãi suất đơn, lãi suất kép, giá trị tương lai, giá trị hiện tại, dòng tiền đều và khấu hao tài sản**.

---

## 1. Thông Tin Chung

- **Chủ đề:** Cấp số cộng, cấp số nhân và ứng dụng trong tài chính.
- **Giảng viên giảng dạy:** Nguyễn Đăng Minh Phúc.
- **Sinh viên thực hiện:** Trần Ngọc Vân Nam.
- **Mã sinh viên:** 23S1010020.
- **Đơn vị:** Trường Đại học Sư phạm, Đại học Huế – Khoa Toán.
- **Định dạng đầu ra:** File PDF được biên soạn bằng LaTeX.
- **Ngôn ngữ:** Tiếng Việt.
- **Công cụ biên soạn:** LaTeX/Overleaf.

---

## 2. Đề Cương Chi Tiết Bài Tiểu Luận

### Lời Nói Đầu

Giới thiệu vai trò của chuỗi số trong toán học và thực tế; nêu ý nghĩa của cấp số cộng, cấp số nhân và sự cần thiết của việc nghiên cứu các ứng dụng của chúng trong lĩnh vực tài chính.

### Chương 1: Cấp Số Cộng

- Khái niệm và định nghĩa cấp số cộng.
- Các ví dụ về cấp số cộng với công sai dương, âm và bằng 0.
- Công thức số hạng tổng quát:
  `u_n = u_1 + (n-1)d`.
- Chứng minh công thức số hạng tổng quát bằng phương pháp quy nạp toán học.
- Công thức tổng n số hạng đầu:
  `S_n = n(u_1+u_n)/2`.
- Công thức tổng theo số hạng đầu và công sai:
  `S_n = n[2u_1+(n-1)d]/2`.
- Chứng minh công thức tổng bằng cách ghép các số hạng cách đều.
- Các tính chất cơ bản:
  - Trung bình cộng.
  - Tổng các số hạng cách đều.
  - Đặc trưng ba số lập thành cấp số cộng.
  - Tạo cấp số cộng mới.
- Các dạng bài tập thường gặp:
  - Xác định cấp số cộng.
  - Tìm số hạng.
  - Tính tổng.

### Chương 2: Cấp Số Nhân

- Khái niệm và định nghĩa cấp số nhân.
- Các ví dụ về cấp số nhân với công bội dương, phân số và âm.
- Công thức số hạng tổng quát:
  `u_n = u_1 q^(n-1)`.
- Chứng minh công thức số hạng tổng quát bằng phương pháp quy nạp.
- Công thức tổng n số hạng đầu và trường hợp `q = 1`.
- Chứng minh công thức tổng bằng phương pháp nhân hai vế với công bội.
- Tổng cấp số nhân vô hạn khi `|q| < 1`.
- Các tính chất cơ bản:
  - Trung bình nhân.
  - Tích các số hạng cách đều.
  - Đặc trưng ba số lập thành cấp số nhân.
  - Tạo cấp số nhân mới.
- Các dạng bài tập thường gặp:
  - Xác định cấp số nhân.
  - Tìm số hạng.
  - Tính tổng.

### Chương 3: Ứng Dụng Trong Tài Chính

- Giới thiệu mối liên hệ giữa cấp số cộng, cấp số nhân và các bài toán tài chính.
- **Lãi suất đơn:**
  - Khái niệm.
  - Công thức tiền lãi.
  - Công thức số tiền sau n kỳ.
  - Mối liên hệ với cấp số cộng.
- **Lãi suất kép:**
  - Khái niệm.
  - Công thức `A_n = P(1+r)^n`.
  - Mối liên hệ với cấp số nhân.
  - Ví dụ tính toán và so sánh với lãi suất đơn.
  - Bảng so sánh lãi suất đơn và lãi suất kép.
- **Giá trị tương lai (Future Value – FV):**
  - Công thức `FV = PV(1+r)^n`.
  - Ý nghĩa của các đại lượng.
- **Giá trị hiện tại (Present Value – PV):**
  - Công thức `PV = FV/(1+r)^n`.
  - Khái niệm hệ số chiết khấu.
- **Dòng tiền đều (Annuity):**
  - Khái niệm.
  - Giá trị tương lai:
    `FVA = A[(1+r)^n-1]/r`.
  - Chứng minh công thức bằng tổng cấp số nhân.
  - Giá trị hiện tại:
    `PVA = A[1-(1+r)^(-n)]/r`.
  - Ví dụ gửi tiết kiệm định kỳ.
- **Khấu hao tài sản:**
  - Khái niệm khấu hao.
  - Khấu hao đường thẳng và mối liên hệ với cấp số cộng.
  - Khấu hao số dư giảm dần và mối liên hệ với cấp số nhân.
  - Bảng so sánh hai phương pháp khấu hao.
- **Ví dụ thực tế:**
  - Trả góp mua ô tô.
  - Phân tích giá trị hiện tại của dòng tiền từ một dự án đầu tư.

### Kết Luận

Tổng hợp kết quả nghiên cứu về cấp số cộng, cấp số nhân và các ứng dụng của chúng trong lĩnh vực tài chính; làm rõ ý nghĩa của việc vận dụng toán học vào các bài toán thực tế.

### Tài Liệu Tham Khảo

Danh mục tài liệu giáo dục, tài liệu về toán tài chính và các công cụ trí tuệ nhân tạo được sử dụng để hỗ trợ quá trình thực hiện dự án.

---

## 3. Kế Hoạch & Tiến Độ Thực Hiện

Dự án được thực hiện trong **2 tuần (14 ngày)** nhằm đảm bảo đủ thời gian nghiên cứu lý thuyết, xây dựng nội dung, kiểm tra các phép tính và hoàn thiện hình thức trình bày.

### Tuần 1: Nghiên Cứu Và Xây Dựng Nội Dung

- **Ngày 1:** Xác định chủ đề, mục tiêu, phạm vi nghiên cứu và hoàn thiện Lời Nói Đầu.
- **Ngày 2:** Nghiên cứu cơ sở lý thuyết về cấp số cộng; tổng hợp định nghĩa, công thức và tính chất.
- **Ngày 3:** Xây dựng các ví dụ và chứng minh công thức của cấp số cộng; hoàn thiện Chương 1.
- **Ngày 4:** Nghiên cứu cơ sở lý thuyết về cấp số nhân; tổng hợp định nghĩa, công thức và tính chất.
- **Ngày 5:** Xây dựng ví dụ, chứng minh các công thức cấp số nhân và hoàn thiện Chương 2.
- **Ngày 6:** Nghiên cứu mối liên hệ giữa cấp số cộng, cấp số nhân và các bài toán tài chính thực tế.
- **Ngày 7:** Xây dựng nội dung về lãi suất đơn, lãi suất kép, giá trị tương lai và giá trị hiện tại.

### Tuần 2: Ứng Dụng, Kiểm Tra Và Hoàn Thiện

- **Ngày 8:** Xây dựng nội dung về dòng tiền đều; thiết lập và kiểm tra các công thức giá trị tương lai và giá trị hiện tại.
- **Ngày 9:** Xây dựng nội dung về khấu hao tài sản; hoàn thiện các ví dụ liên quan đến cấp số cộng và cấp số nhân.
- **Ngày 10:** Hoàn thiện các ví dụ thực tế về trả góp mua ô tô và phân tích giá trị hiện tại của dòng tiền.
- **Ngày 11:** Kiểm tra toàn bộ phép tính, công thức toán học, số liệu và bảng biểu trong Chương 3.
- **Ngày 12:** Hoàn thiện Kết Luận và Tài Liệu Tham Khảo; rà soát tính thống nhất của nội dung.
- **Ngày 13:** Định dạng toàn bộ tài liệu LaTeX: trang bìa, mục lục, tiêu đề chương, bảng, căn lề, giãn dòng và tài liệu tham khảo.
- **Ngày 14:** Biên dịch thử trên Overleaf, sửa lỗi LaTeX, kiểm tra lần cuối toàn bộ PDF và hoàn thiện phiên bản nộp chính thức.

---

## 4. Tài Liệu Tham Khảo & Công Cụ Hỗ Trợ

### Tài liệu tham khảo

1. **Bộ Giáo dục và Đào tạo – Đại số và Giải tích 11**, Nhà xuất bản Giáo dục Việt Nam, 2019.
   - Tài liệu tham khảo về cấp số cộng, cấp số nhân và các kiến thức đại số liên quan.

2. **Bộ Giáo dục và Đào tạo – Đại số và Giải tích 11 nâng cao**, Nhà xuất bản Giáo dục Việt Nam, 2021.
   - Tài liệu tham khảo về lý thuyết, công thức và bài tập liên quan đến cấp số.

3. **Nguyễn Đình Trí – Giáo trình Toán tài chính**, Nhà xuất bản Đại học Kinh tế Quốc dân, 2020.
   - Tài liệu tham khảo về lãi suất, giá trị hiện tại, giá trị tương lai và các bài toán tài chính.

4. **Trần Văn Nhung – Lý thuyết và bài tập cấp số cộng - cấp số nhân**, Nhà xuất bản Đại học Sư phạm Hà Nội, 2019.
   - Tài liệu tham khảo về định nghĩa, tính chất, công thức và các dạng bài tập của cấp số cộng, cấp số nhân.

5. **Phạm Hữu Đắc – Toán cao cấp cho kinh tế**, Nhà xuất bản Thống kê, 2021.
   - Tài liệu tham khảo về các nội dung toán học có ứng dụng trong kinh tế – tài chính.

### Công cụ hỗ trợ

6. **ChatGPT – OpenAI**  
   https://chatgpt.com/  
   - Sử dụng để hỗ trợ tìm hiểu lý thuyết, xây dựng nội dung, kiểm tra cách trình bày và rà soát bài tiểu luận.

7. **Gemini – Google**  
   https://gemini.google.com/  
   - Sử dụng để hỗ trợ tìm kiếm, tham khảo thông tin và kiểm tra nội dung trong quá trình thực hiện dự án.

8. **Google AI**  
   https://ai.google/  
   - Sử dụng để tham khảo các công cụ trí tuệ nhân tạo và hỗ trợ quá trình nghiên cứu, xử lý thông tin.

---

## 5. Cấu Trúc File LaTeX

Dự án sử dụng một file LaTeX chính với các thành phần:

- `report`: lớp tài liệu chính.
- `amsmath`, `amssymb`, `amsthm`: hỗ trợ công thức toán học và môi trường định lý.
- `geometry`: thiết lập lề trang.
- `titlesec`: định dạng tiêu đề chương, mục và tiểu mục.
- `tocloft`: định dạng mục lục.
- `fancyhdr`: thiết lập đầu trang và chân trang.
- `enumitem`: tùy chỉnh danh sách.
- `hyperref`: tạo liên kết trong tài liệu.
- `indentfirst`: thụt đầu dòng.
- `setspace`: thiết lập giãn dòng 1,5.
- `booktabs`, `array`: hỗ trợ trình bày bảng.
- `tikz`, `calc`: tạo khung trang bìa.
- `graphicx`: chèn hình ảnh logo.

### Tài nguyên cần có

Ảnh logo trường được sử dụng trên trang bìa với tên:

```text
logo.jpg
