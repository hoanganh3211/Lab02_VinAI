# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Nguyễn Thành Tiến
- Mã học viên:2A202603003
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Sinh viên sắp tốt nghiệp
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 |Lặp lại |Làm 1 report bằng excel về báo cáo tài chính |nhân viên phân tích dữ liệu |Cùng 1 dạng báo cáo nhưng phải phân tích cơ bản từng cái thủ công, thời gian mất hơn 5 tiếng |
| 2 |Lặp lại |Kiểm tra và đối chiếu dữ liệu giữa 2–3 hệ thống  và có sai sót con người  |Accountant |2-15 phút cho từng tài khoản thủ công|
| 3 |Pain từ người khác |Người ở trọ hỏi lại cùng 1 câu hỏi trong bộ quy định|Chủ nhà cho thuê |Số câu hỏi về quy định chiếm hơn 70%|
| 4 |Lặp lại |Kiểm tra tình trạng trạm sạc trước khi đến nhưng thông tin không cập nhật kịp thời |Tài xế xe điện |Tới nơi mới biết trạm lỗi |
| 5 |Lặp lại |Mỗi cuộc họp phải gửi email mời đến nhiều bên liên quan, sau đó theo dõi phản hồi và nhắc những người chưa xác nhận |Nhân viên điều phối |10–30 người/cuộc họp; 5–10 cuộc họp/tuần; mỗi email mất ~1–2 phút để kiểm tra/chỉnh sửa/gửi |
| 6 |AI có thể tốt hơn |Đọc và tóm tắt nhiều feedback/comment để tìm ra các vấn đề chính |Marketing |Có thể phải xử lý 50–200 feedbacks, nếu đọc thủ công sẽ mất nhiều giờ để phân loại và tổng hợp |
| 7 | | | | |
| 8 | | | | |
| 9 | | | | |
| 10 | | | | |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi:
- Ý dùng được:
- Ý bỏ vì không phải pain thật:

**Self-check Phase 1:**
- [ ] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [ ] Dùng ít nhất 3/4 lăng kính
- [ ] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Gửi số lượng lớn email mời họp và theo dõi phản hồi|Có thể tìm metric đo lường hiệu quả dễ dàng sau khi dùng AI, nhu cầu và hiệu quả cao khi số lượng người dùng càng nhiều  |Chưa đo chính xác tỷ lệ người không phản hồi và tổng thời gian follow-up |
| 2 |Làm report tài chính bằng Excel thủ công |Mất hơn 5 tiếng/report; workflow rõ; có nhiều bước lặp lại; impact trực tiếp lên thời gian của analyst |cần xác định được phần nào nên được AI can thiệp |
| 3 |Kiểm tra tình trạng trạm sạc nhưng thông tin không cập nhật kịp thời |Pain chung của tài xế, có thể ảnh hưởng cả hệ thống xe điện nói chung khi gặp lỗi trên diện rộng |Chi phí lắp đặt để tạo hệ thống AI và duy trì có lớn hơn chi phí khi gặp lỗi không  |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — [Tên problem]

```text
Problem 1 câu:Nhân viên phân tích phải thực hiện nhiều bước xử lý và phân tích thủ công trong Excel để tạo một report tài chính, mất hơn 5 tiếng/report.

Actor:Nhân viên phân tích dữ liệu

Thời điểm / bối cảnh:Khi cần lập báo cáo tài chính định kỳ hoặc phân tích một bộ dữ liệu có cấu trúc tương tự các kỳ trước

Current workflow 3-7 bước:
1. Thu thập dữ liệu. 
2. Kiểm tra và làm sạch dữ liệu. 
3. Nhập/copy dữ liệu vào Excel. 
4. Tính toán các chỉ tiêu tài chính. 
5. Phân tích biến động từng chỉ tiêu. 
6. Tạo bảng/chart. 
7. Tổng hợp thành report cuối cùng.

Bottleneck:Phân tích từng chỉ tiêu và kiểm tra kết quả thủ công. Các bước tính toán và nhận xét lặp lại giữa các kỳ báo cáo. 

Impact:
Một report mất hơn 5 tiếng. Nếu thực hiện nhiều report trong tháng/tuần, thời gian dành cho các thao tác lặp lại chiếm tỷ trọng lớn.

Success metric:
- Giảm thời gian tạo report từ >5 giờ xuống <2 giờ. 
- Giảm số thao tác Excel thủ công. 
- Giảm số lỗi trong công thức/dữ liệu. 
- Analyst dành nhiều thời gian hơn cho việc kiểm tra insight.

Non-AI alternative:

AI hypothesis:
AI có thể tự động kiểm tra dữ liệu, tính các chỉ số, phát hiện biến động bất thường và tạo draft nhận xét cho từng chỉ tiêu.
Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — ___ phút

[1 ...: __'] → [2 ...: __'] → [3 ...: __'] → [4 ...: __']  <-- bottleneck

FUTURE STATE — ___ phút

[1 ...: __'] → [2 ...: __'] → [3 ... review: __']  <-- human boundary

Fallback: nếu AI sai thì ...
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — [Tên problem]

```text
Problem 1 câu:

Actor:

Thời điểm / bối cảnh:

Current workflow 3-7 bước:
1.
2.
3.
4.
5.

Bottleneck:

Impact:

Success metric:

Non-AI alternative:

AI hypothesis:

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — ___ phút

[1 ...] → [2 ...] → [3 ...]  <-- bottleneck

FUTURE STATE — ___ phút

[1 ...] → [2 ...] → [3 ... review]  <-- human boundary

Fallback: ...
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — [Tên problem]

```text
Problem 1 câu:

Actor:

Thời điểm / bối cảnh:

Current workflow 3-7 bước:
1.
2.
3.
4.
5.

Bottleneck:

Impact:

Success metric:

Non-AI alternative:

AI hypothesis:

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — ___ phút

[1 ...] → [2 ...] → [3 ...]  <-- bottleneck

FUTURE STATE — ___ phút

[1 ...] → [2 ...] → [3 ... review]  <-- human boundary

Fallback: ...
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text

```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text

```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text

```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra:
- Tôi sửa gì:

### Self-check nộp phần 01
- [ ] Có 5+ problems + top 3 Cards đủ field
- [ ] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [ ] Đã chọn 1 card pitch + câu hỏi challenge
