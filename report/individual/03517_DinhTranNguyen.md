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


**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |


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
- Vì sao:
- Câu hỏi muốn nhóm phản biện:

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| | | |

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
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
