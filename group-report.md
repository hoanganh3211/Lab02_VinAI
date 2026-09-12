# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Mai Hoàng Anh | 2A202602857 |   Researcher                                                 |
| 2   | Lê Minh Hiếu | 2A202602828 |     Facilitator                                               |
| 3   | Nguyễn Thành Tiến | 2A202603003 |     Workflow                                                  |
| 4   | Vũ Huy Đô | 2A202602555 |     Writer                                                    |
| 5   | Hoàng Văn Sơn | 2A202602375 |    Researcher                                                 |

**Candidate problem nhóm chọn (1 câu): Sinh viên IT gặp khó khăn trong việc định hướng chuyên ngành phù hợp với bản thân**


---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Mai Hoàng Anh | Khó ước lượng và nhập calo đồ ăn ngoài tiệm do thiếu dữ liệu chuẩn | Người thường xuyên ăn ngoài | Tìm món tương đương trên app và tự ước lượng định lượng bằng mắt | Pain thật, lặp lại hàng ngày; nhưng cần dataset món ăn Việt đủ lớn — data access là rào cản |
| 2 | Mai Hoàng Anh | Nhập liệu bữa ăn tự nấu rất tốn thời gian do lặp lại nhiều thao tác | Người tự nấu ăn | Phải search và nhập định lượng lắt nhắt cho từng nguyên liệu | Workflow lặp lại rõ, có thể giải bằng Rule (template bữa ăn mẫu) trước khi cần AI |
| 3 | Mai Hoàng Anh | App không gợi ý thực đơn, người dùng phải tự suy nghĩ món ăn khớp số liệu | Người muốn giảm cân | Tính toán tổ hợp món ăn khớp calo/macro và nguyên liệu hiện có | Thú vị, AI có thể giúp gợi ý tổ hợp; nhưng metric "thực đơn phù hợp" chủ quan, khó đo |
| 4 | Hoàng Văn Sơn | Đối soát & chia tiền chi tiêu chung phòng trọ từ hóa đơn viết tay và bill chuyển khoản | Sinh viên ở ghép phòng trọ | Chủ nhà gửi hóa đơn viết tay (điện, nước, rác), 1 người đóng gom rồi tính toán chia lẻ, thu lại từng người | Rất thực tế, xảy ra hàng tháng, nhưng dùng OCR + Rule là giải quyết được |
| 5 | Hoàng Văn Sơn | Kiểm tra và rà soát bài tập nhóm theo đúng Rubric & yêu cầu của giảng viên | Sinh viên làm bài tập nhóm | Nhóm trưởng/thành viên phải đọc kỹ slide, file yêu cầu, Rubric 10-15 trang rồi soi từng phần bài làm | Cần thiết nhưng bị giới hạn bởi định dạng file đầu vào và cấu trúc bài làm |
| 6 | Hoàng Văn Sơn | Lục tìm lại tài liệu học tập & thông báo deadline bị trôi trong các nhóm Zalo môn học | Sinh viên IT | Mỗi môn 1 nhóm Zalo 40-50 người, tin nhắn trôi nhanh, file/ảnh bị hết hạn không tải lại được | Nỗi đau hàng ngày nhưng Zalo API đóng, rất khó can thiệp kỹ thuật |
| 7 | Nguyễn Thành Tiến | Tài xế phải kiểm tra nhiều nguồn/group để hỏi xem trạm nào đang hoạt động hoặc còn chỗ | Tài xế xe điện | Thông tin về tình trạng trạm phân tán, không có một nguồn cập nhật đáng tin cậy | Pain thật, nhưng phụ thuộc nhiều vào data realtime từ nhà vận hành trạm — data access là rủi ro lớn |
| 8 | Nguyễn Thành Tiến | Tài xế không biết trước trạm nào đang đông hoặc sắp đầy, phải đến nơi mới biết có thể sạc hay không | Tài xế xe điện | Thiếu dự báo tình trạng sử dụng trạm và số cổng sạc còn trống | Cùng nhóm bài #7, scale lớn nhưng cần hạ tầng data sạch, khó validate nhanh trong lab |
| 9 | Nguyễn Thành Tiến | Khi trạm đang bảo trì hoặc quá tải, tài xế phải tự tìm trạm thay thế | Tài xế xe điện | Không có gợi ý trạm thay thế dựa trên khoảng cách, tình trạng hoạt động và mức độ đông | Workflow rõ nhưng nên gộp với bài #7-8; actor ngoài sinh viên, khó validate nhanh |
| 10 | Lê Minh Hiếu | Sinh viên IT gặp khó khăn trong việc định hướng chuyên ngành phù hợp với bản thân | Sinh viên IT năm 2-4 | Tự đánh giá năng lực và đối chiếu thị trường không có tiêu chí rõ, hay chọn theo cảm tính hoặc đám đông (1-4 tuần phân vân) | Pain rộng, evidence mạnh (10/10 SV xác nhận), workflow và metric rõ — candidate hàng đầu của nhóm |
| 11 | Lê Minh Hiếu | Sinh viên IT vừa học vừa làm thêm mất khoảng 2 giờ/tuần lập lịch nhưng vẫn thường xuyên bị overload và bỏ lỡ deadline | Sinh viên năm 3-4 vừa đi học vừa đi thực tập | Phân tích conflict lịch và ưu tiên nhiệm vụ thủ công mà không có tiêu chí rõ (30-40 phút/tuần) | Pain thật của nhiều SV, nhưng metric khó validate dứt khoát; một phần có thể giải bằng Rule/Calendar |
| 12 | Lê Minh Hiếu | Sinh viên IT mất 3-5 giờ tìm việc làm thêm từ nhiều nguồn rời rạc nhưng hay tìm được vị trí không khớp lịch học hoặc tech stack | Sinh viên IT năm 3-4 đang tìm part-time/thực tập | Phải đọc thủ công từng JD để lọc theo tech stack, giờ làm và mức lương cùng lúc (1-1.5 giờ/đợt) | Bottleneck rõ, evidence có (6/6 SV); scope hơi rộng nhưng pilot được với dữ liệu tĩnh |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A — Định hướng / hỗ trợ học tập | #10 (định hướng chuyên ngành), #5 (rà soát bài theo rubric), #6 (tài liệu Zalo bị trôi) | Sinh viên thiếu thông tin cụ thể để ra quyết định học tập hoặc tự kiểm tra | Candidate #10 có workflow và metric rõ nhất |
| B — Theo dõi sức khoẻ / thói quen | #1 (nhập calo ngoài tiệm), #2 (nhập bữa tự nấu), #3 (gợi ý thực đơn) | Lặp lại hàng ngày, AI có thể hỗ trợ matching/gợi ý nhưng cần dataset Việt | Data access là rào cản chung |
| C — Quản lý tài chính / lịch trình | #4 (chia tiền phòng trọ), #11 (cân bằng lịch học-làm), #12 (tìm việc làm thêm) | Tổng hợp thông tin từ nhiều nguồn, lọc theo tiêu chí cá nhân | #4 giải được bằng Rule; #11-12 scope rộng hơn |
| D — Hạ tầng thông tin thời gian thực | #7, #8, #9 (trạm sạc xe điện) | Cần data realtime từ bên thứ 3, actor ngoài sinh viên | Khó validate nhanh trong lab, phụ thuộc data API |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| #10 — Định hướng chuyên ngành IT | Actor rõ (SV IT năm 2-4), workflow 4 bước vẽ được, evidence mạnh (10/10 SV xác nhận pain), metric có thể đo ngắn hạn | Metric dài hạn "chọn đúng" khó validate; AI cần dữ liệu thị trường địa phương |
| #5 — Rà soát bài tập theo Rubric | Workflow rõ (đọc yêu cầu → soi từng phần bài làm), pain thật, AI có thể đọc/so sánh tốt | Phụ thuộc định dạng file đầu vào; quality metric khó chuẩn hoá |
| #12 — Tìm việc làm thêm phù hợp | Evidence có (6/6 SV), bottleneck rõ (lọc JD thủ công), workflow 6 bước | Cần data JD từ nhiều nguồn; scope rộng nếu cần cá nhân hoá cao |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #10 Định hướng chuyên ngành | 5 | 4 | 5 | 4 | 5 | 5 | 5 | 33 |
| #5 Rà soát bài theo Rubric | 4 | 5 | 3 | 3 | 4 | 4 | 4 | 27 |
| #12 Tìm việc làm thêm | 4 | 4 | 4 | 4 | 3 | 4 | 4 | 27 |

**Candidate nhóm chọn (1 bài duy nhất):**

```text
#10 — Sinh viên IT gặp khó khăn trong việc định hướng chuyên ngành phù hợp với bản thân
```

**Vì sao chọn (4-5 câu):**

```text
Bài #10 có actor rõ nhất (sinh viên IT năm 2-4 đang phân vân chuyên ngành), workflow 4 bước có thể vẽ và đo được, và evidence mạnh với 10/10 sinh viên Bách Khoa được phỏng vấn xác nhận pain. Bottleneck ở bước tự đánh giá & đối chiếu thị trường là điểm AI có thể can thiệp cụ thể: phân tích profile sinh viên và match với đặc thù từng chuyên ngành. Impact rõ ràng: sinh viên mất 1-4 tuần phân vân mà vẫn chọn theo cảm tính, dẫn đến học không phù hợp và mất định hướng. Nhóm hiểu domain sinh viên IT tốt nhất, dễ validate và pilot nhanh trong thời gian lab. Metric có thể đo ngắn hạn: tỉ lệ sinh viên xác định được hướng phù hợp trong ≤ 2 giờ.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
#5 — Rà soát bài tập theo Rubric: Workflow rõ nhưng quality metric khó thống nhất — "bài đúng Rubric" phụ thuộc nhiều vào định dạng file và cấu trúc yêu cầu của từng giảng viên, khó chuẩn hoá để AI xử lý chung. Impact cũng khó đo hơn so với bài #10.

#12 — Tìm việc làm thêm: Scope rộng vì cần crawl/collect JD từ nhiều nguồn khác nhau, mỗi nguồn có format riêng. Data access là rủi ro lớn khó giải quyết trong lab; bài #10 có thể pilot hoàn toàn bằng data tĩnh mà không cần external API.

#7-9 — Trạm sạc xe điện: Actor ngoài nhóm sinh viên, cần data realtime từ nhà vận hành, không thể validate nhanh trong thời gian lab.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Một thành viên lo rằng metric "xác định chuyên ngành trong 2 giờ" không đủ để chứng minh AI thực sự hữu ích vì sinh viên có thể chọn nhanh nhưng chọn sai. Nhóm chốt bằng cách thêm metric bổ sung dài hạn (sau 3 tháng, sinh viên có còn theo chuyên ngành đã chọn không) và thêm bước cross-check với mentor/anh chị trong ngành làm human boundary bắt buộc.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview trực tiếp | 10 | 10/10 SV xác nhận pain; 6/10 nói đây là khó khăn lớn nhất| không | Thu hẹp problem: không phải "tìm thông tin chuyên ngành" mà là "không có tiêu chí cá nhân hoá để ra quyết định" |
| Mini poll trong lớp | 8 | 6/8 từng phân vân chuyên ngành ≥ 2 tuần; 5/8 nói thông tin trên mạng nhiều nhưng không áp dụng được cho bản thân | 1 bạn nói trường đã có buổi tư vấn nhưng chung chung, không hữu ích | Thêm non-AI alternative: tư vấn 1-1 với mentor; nhưng không scalable vì thiếu mentor |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Pain thật không nằm ở việc thiếu thông tin về các chuyên ngành — thông tin trên mạng rất nhiều. Pain nằm ở chỗ sinh viên thiếu tiêu chí cá nhân hoá để tự đánh giá xem chuyên ngành nào phù hợp với điểm mạnh, sở thích và mục tiêu nghề nghiệp của riêng mình.
```

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Roadmap.sh | https://roadmap.sh | Cung cấp lộ trình học cho từng chuyên ngành (Frontend, Backend, DevOps, AI...) | Rõ ràng, có cộng đồng lớn, cập nhật thường xuyên | Không cá nhân hoá theo profile sinh viên; sinh viên vẫn phải tự chọn ngành trước | Pattern tốt: có roadmap rõ cho mỗi ngành; nhóm có thể dùng làm reference data khi AI gợi ý |
| LinkedIn Career Explorer | https://linkedin.com/career-advice/career-path | Gợi ý career path dựa trên skills hiện có và kết nối nghề nghiệp | Dữ liệu thực tế từ hàng triệu profile; gợi ý theo thị trường | Thiên về người đã có kinh nghiệm; ít phù hợp với sinh viên mới bắt đầu | AI nên dùng data thị trường thực tế (job posting) thay vì chỉ dựa lý thuyết |
| 16Personalities / career assessment tools | https://www.16personalities.com/career-paths | Phân tích tính cách và gợi ý nghề nghiệp phù hợp | Dễ dùng, có giá trị tham khảo về self-awareness | Không đặc thù ngành IT; không match với thực tế tuyển dụng kỹ thuật | Hướng đi đúng: dùng self-assessment làm input; nhưng cần thêm lớp match với thị trường IT cụ thể |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Không nên build thêm một trang thông tin chuyên ngành nữa — đã có quá nhiều. Hướng hợp lý hơn là Workflow: sinh viên input profile cá nhân (sở thích, điểm mạnh, mục tiêu) → AI phân tích và match với đặc thù từng chuyên ngành IT + nhu cầu thị trường → đưa ra gợi ý có lý giải → sinh viên review với 1 mentor. Quan trọng: AI không thay mentor, chỉ giúp sinh viên đến buổi tư vấn với câu hỏi cụ thể hơn thay vì mơ hồ.
```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

```text
CURRENT STATE — 1-4 tuần phân vân

[1. Tìm kiếm thông tin đa kênh: 3-5h]
→ [2. Học thử dàn trải (Tutorial Hell): vài tuần]
→ [3. Tự đánh giá năng lực & đối chiếu thị trường: 1-4 tuần]  ← BOTTLENECK
→ [4. Chọn chuyên ngành theo cảm tính/đám đông: vài ngày]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | Sinh viên | Không có — tự tìm | Danh sách chuyên ngành nghe qua, video review | 3-5 giờ | Thông tin nhiều nhưng rải rác, không có tiêu chí lọc |
| 2 | Sinh viên | Video tutorial, khoá học thử | Kỹ năng lẻ tẻ, chưa đủ để đánh giá | Vài tuần | Tutorial Hell — học nhiều thứ không có mục tiêu |
| 3 | Sinh viên | Cảm nhận cá nhân, hỏi bạn bè, anh chị | Danh sách so sánh mơ hồ, không có tiêu chí cụ thể | 1-4 tuần | **BOTTLENECK** — không có framework để tự đánh giá phù hợp |
| 4 | Sinh viên | Kết quả bước 3, áp lực đồng trang lứa | Quyết định chọn chuyên ngành | Vài ngày | Hay chọn theo đám đông hoặc cảm tính, dễ hối hận |
| 5 | — | — | — | — | — |
| 6 | — | — | — | — | — |
| 7 | — | — | — | — | — |

**Bottleneck chính (2-3 câu):**

```text
Bước 3 — tự đánh giá năng lực và đối chiếu thị trường — là bottleneck lớn nhất. Sinh viên không có tiêu chí cụ thể nào để trả lời câu hỏi "chuyên ngành này có phù hợp với mình không", không biết điểm mạnh nào của bản thân ánh xạ vào đặc thù nào của ngành. Quá trình này kéo dài 1-4 tuần nhưng thường kết thúc bằng quyết định theo cảm tính.
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
FUTURE STATE — 1 buổi (~2 giờ)

[1. SV input profile cá nhân (sở thích, điểm mạnh, mục tiêu): 15']  -- tự làm
→ [2. AI phân tích & match với đặc thù chuyên ngành + thị trường: 5']  -- Workflow step
→ [3. AI xuất top 2-3 gợi ý có lý giải cụ thể: 2']  -- Workflow step
→ [4. SV review, hỏi thêm, điều chỉnh: 30-60']  -- human boundary
→ [5. SV cross-check với 1 mentor/anh chị trong ngành đó: 30']  -- human boundary

Fallback: Nếu AI gợi ý không sát thực tế thị trường hoặc thiếu context địa phương → SV hỏi thêm mentor và tự điều chỉnh; kết quả AI chỉ là điểm khởi đầu cho cuộc trò chuyện.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian phân vân | 1-4 tuần | ≤ 1 buổi (2 giờ) | Bấm giờ từ khi bắt đầu đến khi có quyết định đủ tự tin |
| Số bước | 4 | 5 | Thêm bước mentor review nhưng giảm thời gian toàn bộ |
| Số bước thủ công không có tiêu chí | 4/4 | 2/5 | SV vẫn review và gặp mentor; AI xử lý bước phân tích |
| Bottleneck chính | Tự đánh giá không tiêu chí (1-4 tuần) | Review & cross-check với mentor (30-60') | Thời gian từ có gợi ý AI đến quyết định cuối |
| Risk mới | Không có | AI gợi ý sai thực tế thị trường địa phương | SV và mentor phát hiện khi cross-check |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên IT năm 2-4 đang phân vân lựa chọn chuyên ngành (AI, Data, Backend, Frontend, DevOps...) để tập trung học tập và xây dựng lộ trình nghề nghiệp. |
| **Workflow** | Sinh viên tìm kiếm thông tin đa kênh → học thử dàn trải → tự đánh giá năng lực và đối chiếu thị trường → chọn chuyên ngành theo cảm tính hoặc đám đông. |
| **Bottleneck** | Bước tự đánh giá và đối chiếu thị trường kéo dài 1-4 tuần vì sinh viên không có tiêu chí cá nhân hoá nào để trả lời "chuyên ngành này có phù hợp với mình không". |
| **Impact** | 10/10 sinh viên BK được phỏng vấn xác nhận pain; 6/10 đánh giá đây là khó khăn lớn nhất. Kết quả: học hành mông lung, chọn sai chuyên ngành, mất thời gian và áp lực đồng trang lứa. |
| **Success Metric** | ≥ 70% sinh viên thử giải pháp có thể xác định được chuyên ngành phù hợp trong ≤ 2 giờ; sau 3 tháng vẫn theo chuyên ngành đã chọn ≥ 80%. |
| **Boundary** | AI không tự quyết định thay sinh viên; không thay thế tư vấn mentor; chỉ phân tích profile và đưa ra gợi ý có lý giải; kết quả cần được sinh viên và mentor xác nhận. |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ: Success Metric "70% xác định được" — đo bằng cách nào, ai xác nhận "phù hợp"?
- Tôi sửa gì: Thêm metric bổ sung dài hạn (3 tháng sau có còn theo chuyên ngành không) và thêm điều kiện "không tăng số lần hỏi lại mentor sau buổi tư vấn đầu".

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [ ] Thấp (có đúng/sai rõ) / [x] Cao (nhiều cách trả lời vẫn OK) — Vì sao: Không có một chuyên ngành nào "đúng" cho tất cả; gợi ý phụ thuộc vào profile, sở thích và mục tiêu cá nhân của từng sinh viên — nhiều profile khác nhau đều có thể hợp lý.
- Độ phức tạp: [ ] Thấp (1-2 bước) / [x] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao: Cần phân tích profile sinh viên (nhiều chiều: sở thích, điểm mạnh, mục tiêu), đối chiếu với đặc thù từng chuyên ngành và dữ liệu thị trường tuyển dụng — 3+ nguồn thông tin phụ thuộc nhau.

**Bài toán nhóm nằm ở ô nào:**

```text
Độ mơ hồ CAO + Độ phức tạp CAO → Ô phù hợp nhất với Agent — cần AI tự thu thập dữ liệu đa nguồn, phân tích cá nhân hoá và có thể hỏi thêm SV trong quá trình.
```

**Vì sao (2-3 câu):**

```text
Bài toán có độ mơ hồ cao vì không có đáp án chuyên ngành nào “đúng” tuyệt đối — gợi ý phụ thuộc hoàn toàn vào profile cá nhân. Độ phức tạp cao vì cần tổng hợp nhiều nguồn (profile sinh viên, đặc thù từng ngành, dữ liệu thị trường tuyển dụng địa phương) và có thể cần hỏi thêm SV khi thông tin chưa đủ. Agent phù hợp hơn Workflow vì có thể tự lấy dữ liệu thị trường động, điều chỉnh gợi ý khi có thêm context, và xử lý các nhánh khác nhau tuyỳ profile.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Template self-assessment cố định + bảng so sánh chuyên ngành tĩnh | Đủ nếu sinh viên chỉ cần thông tin tổng quan và tự điền checklist | Không cá nhân hoá; không phân tích được profile sâu; sinh viên vẫn phải tự kết luận | Không chọn làm toàn bộ; dùng để cấu trúc form input của sinh viên |
| **Workflow** | SV input profile → AI phân tích & match → AI xuất gợi ý có lý giải → SV review → cross-check với mentor | Hợp vì workflow tuyến tính, input rõ (profile SV), output rõ (top 2-3 gợi ý), AI chỉ hỗ trợ bước phân tích | AI gợi ý sai thực tế thị trường địa phương; không cập nhật xu hướng tuyển dụng real-time | **Chọn** — dùng cho bước phân tích profile và tạo gợi ý có lý giải |
| **Agent** | Agent tự tìm data thị trường, hỏi thêm SV, so sánh nhiều nguồn, tự cập nhật gợi ý theo thời gian | Chỉ cần nếu muốn real-time job market data và workflow nhiều nhánh phức tạp | Phụ thuộc nhiều API bên ngoài, nhiều permission, khó kiểm soát chất lượng output | Chưa chọn — workflow hiện tại không cần AI tự lập kế hoạch động |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule có giải được 70-80% case không? **Không** — template tĩnh không cá nhân hoá được và không có data thị trường địa phương; sinh viên vẫn phải tự kết luận.
2. Các bước có đi thẳng một đường không hay phải rẽ nhánh? **Có rẽ nhánh** — nếu SV khai thiếu thông tin, Agent cần hỏi thêm; nếu data thị trường thiếu, Agent cần tự tìm thêm — không có một đường thẳng cố định.
3. Có thật sự cần Agent tự lập kế hoạch + gọi tool không? **Có** — cần tự lấy data thị trường địa phương, tự hỏi thêm SV khi thiếu context, tự điều chỉnh gợi ý theo thông tin mới — Workflow thuần túy không đáp ứng được.
4. Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu? **Sinh viên + mentor** phát hiện khi cross-check — trong vòng 30-60 phút, hậu quả chấp nhận được vì SV chưa cam kết chọn ngành.
5. Có hạ được từ Agent → Workflow → Rule không? **Có** — pilot có thể bắt đầu bằng Workflow bán thủ công để kiểm chứng nhanh, nhưng độ phức tạp và độ mơ hồ cao cho thấy Agent sẽ tạo gợi ý chất hơn dài hạn.

**Mức chọn:**

```text
Agent
```

**Vì sao chọn (3-4 câu):**

```text
Agent phù hợp vì bài toán có độ mơ hồ cao (không có đáp án đúng/sai) và độ phức tạp cao (cần tổng hợp đa nguồn, có nhánh). Agent có thể tự lấy dữ liệu thị trường tuyển dụng địa phương, hỏi thêm SV khi thông tin chưa đủ, và điều chỉnh gợi ý theo từng profile mà Workflow thuần túy không làm được. Sinh viên và mentor vẫn là người review và ra quyết định cuối — Agent chỉ hỗ trợ bước phân tích và cá nhân hoá gợi ý.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Rule không đủ vì không cá nhân hoá và không giải bottleneck. Workflow được nhưng thiếu khả năng xử lý khi dữ liệu SV khai chưa đủ hoặc khi cần data thị trường địa phương mà SV không có — đời hỏi AI phải tự đi tìm thêm. Với độ phức tạp của bài (nhiều nguồn, nhiều nhánh), Agent là mức phù hợp nhất.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên IT năm 2-4 đang phân vân lựa chọn chuyên ngành để tập trung học và xây dựng lộ trình nghề nghiệp. |
| **Workflow** | SV input profile (sở thích, điểm mạnh, mục tiêu) → AI phân tích và match với đặc thù chuyên ngành + thị trường → AI xuất top 2-3 gợi ý có lý giải → SV review & hỏi thêm → cross-check với mentor. |
| **Bottleneck** | Bước tự đánh giá & đối chiếu thị trường kéo dài 1-4 tuần vì không có tiêu chí cá nhân hoá; AI thay thế bước này bằng phân tích có cấu trúc trong ~5 phút. |
| **Impact** | 10/10 SV xác nhận pain; 6/10 đánh giá đây là khó khăn lớn nhất khi học IT. Hệ quả: học dàn trải, chọn sai ngành, mất định hướng và áp lực đồng trang lứa. |
| **Success Metric** | ≥ 70% SV thử giải pháp xác định được chuyên ngành trong ≤ 2 giờ (ngắn hạn); ≥ 80% còn theo chuyên ngành đó sau 3 tháng (dài hạn); không tăng số câu hỏi mơ hồ SV phải hỏi lại mentor. |
| **Boundary** (làm / không làm) | Làm: phân tích profile, tạo gợi ý có lý giải, giúp SV chuẩn bị câu hỏi cho mentor. Không làm: tự quyết định thay SV, thay thế buổi tư vấn với mentor, bịa thông tin thị trường không có nguồn. |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | Sau khi SV hoàn thành form input profile (bước 1), trước khi SV bắt đầu phân vân và tự so sánh chuyên ngành thủ công (bước 3 cũ). |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | **Agent** — vì bài có độ phức tạp cao và độ mơ hồ cao, cần AI tự thu thập dữ liệu đa nguồn, xử lý đa nhánh và cá nhân hoá sâu hơn Workflow thuần túy. |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | Rủi ro: AI gợi ý không sát thực tế thị trường địa phương hoặc overfit theo một profile mẫu. Người kiểm tra: sinh viên review gợi ý và mentor/anh chị trong ngành xác nhận trước khi SV cam kết chọn. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | Yes | Actor: SV IT năm 2-4. Workflow 5 bước tuyến tính, vẽ được và đo được. |
| Baseline + metric đo được chưa? | Yes | Baseline: 1-4 tuần phân vân. Metric: ≤ 2 giờ để xác định hướng; ≥ 80% giữ nguyên quyết định sau 3 tháng. |
| Data/input đủ dùng chưa? | Yes | Input là profile SV tự khai — không cần external API. Có thể pilot hoàn toàn bằng data tĩnh. |
| AI sai, hậu quả chấp nhận được không? | Yes | SV chưa ra quyết định cuối; gợi ý AI chỉ là điểm khởi đầu; mentor review trước khi cam kết. Hậu quả sai: mất 30-60' buổi tư vấn — chấp nhận được. |
| Có người review/owner không? | Yes | Sinh viên review output AI; mentor/anh chị trong ngành xác nhận trước khi SV quyết định. |
| Có cách non-AI đơn giản hơn không? | Yes | Template self-assessment + bảng so sánh chuyên ngành tĩnh có thể thay một phần; nhưng không giải được bước cá nhân hoá và lý giải theo profile cụ thể. |

**Decision:**

```text
Go — với scope nhỏ (pilot workflow bán thủ công)
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Problem rõ (10/10 SV xác nhận), workflow và metric đã được định nghĩa, input không cần external API và có thể pilot ngay bằng data tĩnh. Risk hallucination được kiểm soát bằng bước mentor review bắt buộc trước khi SV ra quyết định. Non-AI alternative (template tĩnh) không giải được bước cá nhân hoá. Điều kiện Go được đáp ứng đủ để chạy pilot nhỏ và đo kết quả trong 1-2 tuần.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
Data: form input profile của 5-10 sinh viên IT tình nguyện (sở thích, điểm mạnh, mục tiêu, môn học yêu thích).
Chạy tay: SV điền form → paste vào prompt chuẩn đã chuẩn bị → AI xuất gợi ý → SV review → gặp mentor 30'
3 số đo: (1) Thời gian từ điền form đến có gợi ý (target ≤ 10 phút), (2) Tỉ lệ SV thấy gợi ý hữu ích (≥ 70%), (3) Tỉ lệ SV vẫn theo chuyên ngành đã chọn sau 4 tuần (≥ 80%).
```

**Nếu Not Yet — cần validate gì trước:**

```text
Không áp dụng — nhóm chọn Go.
```

**Nếu No-Go — làm gì thay AI:**

```text
Không áp dụng — nhóm chọn Go.
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
- Nếu ≥ 50% SV phải viết lại hoàn toàn gợi ý của AI sau buổi mentor trong 2 tuần liên tiếp → hạ xuống template tĩnh + checklist.
- Nếu AI bịa thông tin thị trường không có nguồn kiểm chứng → thêm disclaimer bắt buộc và giới hạn AI chỉ phân tích profile, không phát biểu về thị trường.
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [x] Có validation (quote thật) + research (link kiểm được)
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
