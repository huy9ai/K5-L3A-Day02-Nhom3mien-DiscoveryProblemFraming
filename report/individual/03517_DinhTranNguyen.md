# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Đinh Trần Nguyên
- MSSV: 2A202603517
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm:Nhom3mien
- Link repo nhóm: https://github.com/huy9ai/K5-L3A-Day02-Nhom3mien-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại |Khi cần cập nhật tiến độ đồ án cho giảng viên, tôi muốn nắm được công việc và mức độ đóng góp của từng thành viên từ GitHub và Jira, để tổng hợp báo cáo tiến độ nhóm một cách đầy đủ và chính xác.| Nhóm trưởng đồ án.|Ước tính 15 phút/người để đọc commit, kiểm tra time spent và ghi lại. Với 5 thành viên, khoảng 75 phút/lần. |
| 2 | Lặp lai|Khi có thành viên mới tham gia đồ án, tôi muốn họ có thể tự thiết lập môi trường và chạy dự án theo hướng dẫn rõ ràng để giảm thời gian tôi phải trực tiếp hỗ trợ. |Nhóm trưởng đồ án | Từng phải hướng dẫn thành viên mới lấy code, cài công cụ, thư viện, cấu hình biến môi trường và chạy thử. Tài liệu hiện tại thiếu hướng dẫn theo trình tự. Mỗi lần hỗ trợ có thể mất khoảng 1 giờ.|
| 3 | Cần đọc, tổng hợp thông tin|Khi gặp vấn đề kiến thức trong lúc làm lab, tôi muốn tìm lại đúng nội dung trong slide và tài liệu tham khảo để hiểu và áp dụng kiến thức vào bài làm. |Người học |Trong bài lab gần nhất, mất khoảng 2 giờ đọc lại tài liệu Machine Learning và cú pháp code trước khi làm bài. |
| 4 | Lặp lại |Khi chuẩn bị nộp bài lab, tôi muốn kiểm tra tính đầy đủ của các file và mức độ tuân thủ rubric, checkpoint để tránh bỏ sót yêu cầu trước deadline. |Sinh viên làm bài lab | Từng phát hiện thiếu một bài sau khi đã hết hạn nộp. Hiện phải đọc rubric, kiểm tra thủ công file, cấu trúc thư mục và cách đặt tên.|
| 5 | Pain từ người khác|Khi nhận user story trên Jira, tôi muốn có description và Definition of Done rõ ràng để hiểu yêu cầu, bắt đầu làm việc mà không phải hỏi lại PM. |Thành viên nhận task | Từng có user story thiếu description và DoD, khiến người nhận phải dừng công việc để hỏi lại. PM phải kiểm tra và cập nhật task, phát sinh thời gian chờ.|

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3


| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Kiểm tra bài nộp theo Rubric và Checkpoint | Từng hiểu thiếu yêu cầu và bỏ sót một bài, chỉ phát hiện sau deadline. Hậu quả ảnh hưởng trực tiếp đến tính đầy đủ của bài nộp. Ưu tiên cao vì mức độ ảnh hưởng lớn, có thể kiểm chứng bằng số yêu cầu bắt buộc bị bỏ sót. | Chưa xác định nguyên nhân chính là hiểu thiếu yêu cầu hay đối chiếu chưa đầy đủ; chưa biết vấn đề phổ biến đến mức nào. |
| 2 | Task trên Jira thiếu Description và Definition of Done (DoD) | Có tình huống thực tế khiến thành viên phải chờ PM bổ sung thông tin khoảng 10 phút. Actor, workflow và bottleneck rõ ràng, dễ thử nghiệm giải pháp. | Mới ghi nhận một lần, chưa rõ tần suất và liệu issue template/checklist có đủ giải quyết vấn đề. |
| 3 | Tìm lại kiến thức trong slide khi làm lab | Từng mất khoảng 30 phút tìm kiến thức trong nhiều file slide. Có thể đo lường thời gian tìm kiếm và so sánh giải pháp thủ công với AI. | Chưa biết vấn đề có phổ biến không; chưa kiểm chứng hiệu quả của mục lục slide hoặc tìm kiếm bằng AI. |



### Problem Card #1 — Task thiếu Description và DoD

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận một user story trên Jira, tôi muốn có description và Definition of Done (DoD) rõ ràng, để hiểu yêu cầu và bắt đầu làm việc mà không phải hỏi lại PM. |
| Actor | Thành viên nhận task. |
| Thời điểm / bối cảnh | Khi thành viên nhận user story được PM giao trên Jira. |
| Quy trình hiện tại (3–7 bước) | (1) PM tạo user story → (2) Thành viên đọc task → (3) Phát hiện thiếu thông tin và hỏi PM → (4) PM kiểm tra, cập nhật → (5) Thành viên tiếp tục công việc. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Giai đoạn bước 3–4: thành viên phải dừng công việc, hỏi và chờ PM bổ sung thông tin. Tổng thời gian chờ khoảng 10 phút (ước tính); chưa tách được thời gian từng bước. |
| Impact (nếu không giải thì sao) | Thành viên bị gián đoạn, phải chờ thông tin; PM phải kiểm tra và cập nhật lại task. Đã quan sát một lần, chưa xác định tần suất. |
| Success metric (baseline → target) | Thời gian chờ bổ sung thông tin: khoảng 10 phút → tối đa 5 phút (target giả thuyết). |
| Phương án không dùng AI | Jira issue template có description và DoD; checklist kiểm tra thông tin trước khi giao task. |
| Giả thuyết về AI (nếu có) | AI có thể kiểm tra user story trước khi giao, phát hiện trường thiếu và đề xuất câu hỏi để PM bổ sung. Cần kiểm chứng hiệu quả so với template/checklist. |
| Cảm nhận nhanh | Rule / Workflow (sơ bộ; chưa cần Agent). |

**Quy trình nháp hiện tại (ASCII)**

```text
[1. PM tạo user story]
(? phút, chưa đo)
        ↓
[2. Thành viên nhận và đọc task]
(? phút, chưa đo)
        ↓
[3. Phát hiện thiếu thông tin, hỏi PM]
(? phút, chưa đo)
        ↓
[4. PM kiểm tra và cập nhật task]
(? phút, chưa đo)
        ⚠️ BOTTLENECK: BƯỚC 3–4
        Tổng thời gian chờ ~10 phút
        ↓
[5. Thành viên đọc lại và tiếp tục]
(? phút, chưa đo)
```


### Problem Card #2 — Tìm lại kiến thức khi làm lab

| Trường | Nội dung |
|---|---|
| Job Story | Khi gặp phần kiến thức chưa nắm rõ trong lúc làm lab, tôi muốn tìm lại đúng nội dung trong slide để hiểu và áp dụng kiến thức vào bài làm. |
| Actor | Người học / AI Developer. |
| Thời điểm / bối cảnh | Khi làm bài lab cần sử dụng lại kiến thức Machine Learning và cú pháp code đã học. |
| Quy trình hiện tại (3–7 bước) | (1) Đọc yêu cầu lab → (2) Tìm nội dung trong nhiều file slide → (3) Đọc lại kiến thức và syntax → (4) Áp dụng vào bài lab. Bước 3–4 có thể diễn ra đan xen. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2: tìm đúng nội dung trong nhiều file slide, khoảng 30 phút (ước tính). Đây là bước nghẽn về tìm kiếm thông tin, không khẳng định là bước dài nhất của toàn bộ quá trình học. |
| Impact (nếu không giải thì sao) | Mất thời gian tìm lại kiến thức trước khi áp dụng vào bài. Trong một lần làm lab, tổng thời gian khoảng 2 giờ, gồm 30 phút tìm và 90 phút vừa đọc vừa thực hành. |
| Success metric (baseline → target) | Thời gian tìm đúng nội dung trong slide: khoảng 30 phút → 15 phút (target giả thuyết). |
| Phương án không dùng AI | Tạo mục lục slide theo chủ đề, đánh dấu trang quan trọng, chuẩn hóa tên file và liên kết ghi chú với slide gốc. |
| Giả thuyết về AI (nếu có) | AI có thể tìm kiếm ngữ nghĩa trên tập slide và chỉ ra file/trang liên quan, kèm nguồn để người học kiểm chứng. Chưa kiểm chứng độ chính xác hoặc thời gian tiết kiệm. |
| Cảm nhận nhanh | Workflow (sơ bộ; có thể so sánh với phương án không AI). |

**Quy trình nháp hiện tại (ASCII)**

```text
[1. Đọc yêu cầu lab]
(? phút, chưa đo)
        ↓
[2. Tìm nội dung trong nhiều file slide]
(~30 phút)
        ⚠️ BOTTLENECK: TÌM KIẾM TÀI LIỆU
        ↓
[3. Đọc lại kiến thức ML và syntax]
(? phút riêng, chưa đo)
        ↓
[4. Áp dụng kiến thức vào bài lab]
(? phút riêng, chưa đo)

Bước 3–4: ~90 phút cộng lại,
thực tế có thể diễn ra đan xen.

Tổng thời gian quan sát: ~120 phút.
```


### Problem Card #3 — Kiểm tra bài nộp theo Rubric

| Trường | Nội dung |
|---|---|
| Job Story | Khi chuẩn bị nộp bài lab, tôi muốn đối chiếu bài làm với rubric và checkpoint để bảo đảm đã hiểu và đáp ứng đầy đủ các yêu cầu trước deadline. |
| Actor | Sinh viên thực hiện và nộp bài lab. |
| Thời điểm / bối cảnh | Trước khi nộp bài lab, đặc biệt khi cần kiểm tra các yêu cầu bắt buộc trong rubric và checkpoint. |
| Quy trình hiện tại (3–7 bước) | (1) Hoàn thành bài lab → (2) Đọc lại rubric và checkpoint → (3) Kiểm tra file, cấu trúc thư mục, tên file → (4) Đối chiếu bài làm với yêu cầu → (5) Nộp bài. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Nghi ngờ bước 2 và 4 là điểm nghẽn vì từng hiểu thiếu yêu cầu. Tổng thời gian kiểm tra khoảng 15–20 phút (ước tính), chưa đo thời gian từng bước và chưa xác định bước nghẽn nặng nhất. |
| Impact (nếu không giải thì sao) | Có nguy cơ bỏ sót yêu cầu bắt buộc. Từng phát hiện thiếu một bài sau deadline do hiểu thiếu yêu cầu. |
| Success metric (baseline → target) | Số yêu cầu bắt buộc bị bỏ sót sau kiểm tra: đã ghi nhận 1 lần bỏ sót bài → mục tiêu 0 yêu cầu bị bỏ sót trong một bài lab thử nghiệm. Đây chưa phải baseline thống kê theo số bài lab. |
| Phương án không dùng AI | Checklist theo từng mục rubric; bảng đối chiếu yêu cầu với file/phần bài làm; script kiểm tra cấu trúc thư mục và file bắt buộc. |
| Giả thuyết về AI (nếu có) | AI có thể tách rubric thành các yêu cầu cụ thể, đối chiếu với bài làm và chỉ ra mục cần kiểm tra lại. Người học phải xác nhận kết quả, không để AI tự quyết định bài đã đạt. |
| Cảm nhận nhanh | Rule / Workflow (sơ bộ; chưa cần Agent). |

**Quy trình nháp hiện tại (ASCII)**

```text
[1. Hoàn thành bài lab]
(? phút, ngoài thời gian kiểm tra)
        ↓
[2. Đọc lại rubric và checkpoint]
(? phút, chưa đo)
        ⚠️ NGHI VẤN BOTTLENECK
        ↓
[3. Kiểm tra file, cấu trúc thư mục, tên file]
(? phút, chưa đo)
        ↓
[4. Đối chiếu bài làm với từng yêu cầu]
(? phút, chưa đo)
        ⚠️ NGHI VẤN BOTTLENECK
        ↓
[5. Nộp bài]
(? phút, chưa đo)

Tổng thời gian kiểm tra:
Bước 2–4 khoảng 15–20 phút (ước tính).

Chưa xác định bước mất thời gian nhiều nhất.
```



### Card muốn pitch nhất

- Card số: 3
- Vì sao: Vì bản thân đã từng hiểu thiếu yêu cầu, dẫn đến bỏ sót một bài và chỉ phát hiện sau deadline. So với các vấn đề chủ yếu gây mất thời gian, việc bỏ sót yêu cầu có thể ảnh hưởng trực tiếp đến kết quả bài lab và khó khắc phục khi đã hết hạn nộp. Điểm khó không chỉ nằm ở việc kiểm tra file mà còn ở việc hiểu đúng, tổng hợp và đối chiếu các yêu cầu từ nhiều tài liệu như README, RUBRIC và CHECKPOINTS với bài làm thực tế. Tôi đánh giá đây là vấn đề có mức độ ảnh hưởng cao, xuất phát từ trải nghiệm thực tế và cần được tìm hiểu, kiểm chứng thêm trước khi xác định hướng giải quyết.
- Câu hỏi muốn nhóm phản biện: Nguyên nhân chính khiến học viên bỏ sót yêu cầu khi nộp bài là do chưa hiểu đầy đủ nội dung trong rubric, do yêu cầu nằm phân tán ở nhiều tài liệu, hay do chưa đối chiếu đầy đủ bài làm với các yêu cầu trước khi nộp? Vấn đề này có thường xuyên xảy ra với các học viên khác hay chỉ là trường hợp cá nhân?

### AI đã phản biện card thế nào


| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Chưa xác định chính xác bottleneck: chưa rõ khó khăn nằm ở việc hiểu rubric hay đối chiếu bài làm với yêu cầu. | Đồng ý | Xác định bước 2 (đọc lại rubric và checkpoint) và bước 4 (đối chiếu bài làm) là hai bước nghi ngờ có bottleneck, chưa khẳng định bước nào mất nhiều thời gian nhất. |
| Bằng chứng còn hạn chế, mới dựa trên một trải nghiệm cá nhân nên chưa thể kết luận vấn đề phổ biến với nhiều học viên. | Đồng ý | Ghi rõ đã quan sát một lần bỏ sót bài do hiểu thiếu yêu cầu, chưa xác định tần suất. Đề xuất tiếp tục kiểm chứng với các học viên khác. |
| Baseline chưa đủ rõ: thời gian kiểm tra 15–20 phút chỉ là ước tính, chưa có dữ liệu đo lường qua nhiều bài lab. | Đồng ý | Phân biệt số liệu ước tính với dữ liệu đã quan sát. Giữ mục tiêu không bỏ sót yêu cầu bắt buộc trong bài lab thử nghiệm dưới dạng giả thuyết, chưa xem là kết quả đã kiểm chứng. |
| Có nguy cơ tập trung vào giải pháp AI trước khi hiểu rõ nguyên nhân của vấn đề. | Đồng ý | Tập trung mô tả actor, quy trình, bottleneck và hậu quả của việc hiểu thiếu yêu cầu. Chưa lựa chọn giải pháp hay mặc định cần sử dụng AI. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---


## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Sử dụng AI để phân tích và làm rõ 5 vấn đề từ trải nghiệm cá nhân theo các lăng kính: lặp lại, tốn thời gian, cần tổng hợp thông tin và pain từ người khác. Nhờ AI hỗ trợ viết Job Story, xác định actor và dấu hiệu thực tế. | Giúp diễn đạt vấn đề rõ ràng, phân biệt người chịu ảnh hưởng và tình huống phát sinh. Gợi ý những thông tin còn thiếu để có thể đánh giá vấn đề. | AI có lúc diễn giải chưa chính xác số liệu và nguyên nhân. Ví dụ, gộp toàn bộ 2 giờ làm lab thành thời gian tìm kiếm tài liệu, hoặc dễ hiểu nhầm việc bỏ sót bài là do quên kiểm tra thay vì hiểu thiếu yêu cầu. | Tôi làm rõ rằng thời gian tìm slide khoảng 30 phút, còn 90 phút dành cho đọc và thực hành. Tôi xác nhận việc bỏ sót bài xuất phát từ hiểu thiếu yêu cầu. Với Jira, tôi chỉ ghi nhận một tình huống thiếu Description/DoD, không suy rộng thành vấn đề xảy ra thường xuyên. |
| CP2 Problem Card | Nhờ AI xây dựng 3 Problem Cards, mô tả workflow bằng ASCII, xác định bottleneck, impact, success metric và phản biện các giả định. | Giúp tách từng bước trong quy trình, phân biệt số liệu quan sát với ước tính, nhận diện các bottleneck chưa được đo và đề xuất cách kiểm chứng. | AI ban đầu xếp vấn đề Jira thiếu Description/DoD ở Rank 1 dựa trên điểm đánh giá. Một số nhận định về bottleneck và mức độ phổ biến cũng chưa có đủ bằng chứng. AI còn có xu hướng đề cập giải pháp AI quá sớm. | Tôi thay đổi thứ hạng, đưa vấn đề kiểm tra bài nộp theo Rubric và Checkpoint lên Rank 1 vì hậu quả bỏ sót yêu cầu sau deadline nghiêm trọng hơn việc mất thêm thời gian. Tôi chọn Card #3 để pitch, yêu cầu tách vấn đề khỏi giải pháp AI, chỉ giữ các bottleneck ở mức nghi vấn và không tự tạo số liệu cho từng bước. |
| CP4 Research | Nhờ AI hỗ trợ xây dựng Assumption Map, thiết kế câu hỏi phỏng vấn, minh họa cách ghi Interview Snapshot và nghiên cứu các giải pháp hiện có. | Giúp chuyển vấn đề thành giả định có thể kiểm chứng, xây dựng câu hỏi dựa trên trải nghiệm thực tế và phân biệt tín hiệu xác nhận với tín hiệu phản bác. AI cũng hỗ trợ so sánh GitHub Task Lists, NotebookLM và GitHub Actions. | AI ban đầu đề xuất nhiều giả định và cách trình bày chưa hoàn toàn bám sát cấu trúc báo cáo. Các interview snapshot do AI tạo chỉ là dữ liệu giả lập, không thể xem là bằng chứng phỏng vấn thật. | Tôi chọn tập trung vào giả định: "Việc hiểu thiếu yêu cầu lab có thể dẫn đến bỏ sót nội dung bắt buộc khi nộp bài". Tôi yêu cầu giữ nguyên template, không tự thêm cấu trúc. Tôi cũng yêu cầu sửa tình huống P3 thành vấn đề thông tin chưa thống nhất giữa các file hướng dẫn, ví dụ cách đặt tên repository. Tôi phân biệt dữ liệu giả lập với kết quả kiểm chứng thực tế. |
| CP5 Quy trình | Trong các trao đổi trước đó, tôi sử dụng AI để mô tả quy trình hiện tại của việc kiểm tra bài nộp và xác định các bước có thể phát sinh khó khăn. Chưa có đủ thông tin để ghi nhận một lần làm việc riêng nhằm hoàn thiện CP5 của nhóm. | AI giúp mô tả trình tự: hoàn thành lab → đọc rubric/checkpoint → kiểm tra file và cấu trúc → đối chiếu yêu cầu → nộp bài. | AI chưa có dữ liệu thời gian riêng cho từng bước nên không thể xác định chính xác bước nào gây nghẽn lớn nhất. | Tôi yêu cầu ghi rõ thời gian kiểm tra 15–20 phút chỉ là ước tính tổng, không chia thời gian giả định cho từng bước. Tôi cũng phân biệt khó khăn trong việc hiểu yêu cầu với việc kiểm tra sự tồn tại của file. |
| CP5–6 Problem Statement | Sử dụng AI để thảo luận cách diễn đạt lại problem sau phần kiểm chứng minh họa, tập trung vào khó khăn khi tổng hợp, hiểu và đối chiếu yêu cầu từ nhiều tài liệu. Chưa xác nhận đã hoàn thiện Problem Statement chính thức ở CP5–6. | AI giúp nhận diện thêm khả năng thông tin nằm phân tán hoặc chưa thống nhất giữa README, CHECKPOINTS, RUBRIC và SUBMISSION. | AI có nguy cơ kết luận vấn đề đã được xác nhận dựa trên các tình huống phỏng vấn giả lập hoặc mở rộng nguyên nhân khi chưa có bằng chứng thực tế. | Tôi yêu cầu bổ sung trường hợp thông tin mâu thuẫn giữa các file, đồng thời giữ trọng tâm vào vấn đề của người học thay vì mô tả sẵn giải pháp. |
| CP6 Mức can thiệp / quyết định | Nhờ AI nghiên cứu và so sánh những hướng can thiệp có thể áp dụng cho việc kiểm tra yêu cầu bài lab, gồm checklist thủ công, công cụ hỗ trợ tra cứu tài liệu và script kiểm tra tự động. Chưa ghi nhận quyết định CP6 chính thức của nhóm. | AI giúp chỉ ra rằng một số yêu cầu như tên file, cấu trúc thư mục có thể kiểm tra bằng quy tắc, trong khi yêu cầu mang tính ngữ nghĩa cần được xem xét riêng. | AI có xu hướng đề xuất công cụ hoặc AI Agent trước khi chứng minh sự cần thiết. Chưa có thử nghiệm thực tế để kết luận phương án nào hiệu quả nhất. | Tôi yêu cầu tách vấn đề khỏi giải pháp, không mặc định phải sử dụng AI. Tôi ưu tiên làm rõ nguyên nhân, bằng chứng và mức độ ảnh hưởng trước khi lựa chọn phương án can thiệp. |


## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Nhóm có gặp trường hợp bị "solution-first", điều này khá dễ nhận ra khi trong cách bạn trình bày bạn luôn đề cập đến các từ khóa như "đọc", "viết", "hỗ trợ' trong khi cái đang trình bày là vấn đề và nỗi đau của người dùng. 
Tôi đã nhận ra và chỉ ra những từ khóa đó cho bạn và cả nhóm cùng điều hướng bạn quay lại đi từ vấn đề bạn nhận thấy, quy trình xuất hiện vấn đề thực sự là nghẽn ở điểm nào, xác định xem đây là diễn ra 1 lần hay là việc lặp lại thường xuyên.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Tuy chỉ có phỏng vấn sâu 2 cá nhân nhưng kết quả phỏng vấn thực sự chứng minh vấn đề tôi gặp phải là điều mọi người cũng đang gặp. Nhưng đó chỉ là giả định của tôi và mọi người khi mới tiếp nhận Chương Trình nên thời gian làm quen chưa đủ để thích nghi ngay

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
