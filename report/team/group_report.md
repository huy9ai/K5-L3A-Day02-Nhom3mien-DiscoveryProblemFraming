# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: Nhóm 3 miền
- Thành viên: xem `TEAM.md`
- Candidate problem đề xuất ở CP3: Sinh viên cần đối chiếu bài lab với rubric/checkpoint trước khi nộp để tránh bỏ sót yêu cầu bắt buộc.
- Quyết định cuối: Not Yet 

---

## 2. Hội tụ nhóm (CP3)

> **Bản tổng hợp và đề xuất từ báo cáo cá nhân, chờ nhóm thảo luận xác nhận.** Có 4 thành viên, chọn 3 candidate/người, tổng cộng 12 candidate. Chọn theo actor, quy trình, dấu hiệu pain, khả năng đo impact và khả năng kiểm chứng trong lab; không ưu tiên chỉ vì có thể dùng AI. Số liệu bên dưới được giữ đúng mức độ chắc chắn của nguồn cá nhân, chưa phải kết quả kiểm chứng CP4.
>
> Nhóm đã yêu cầu AI hỗ trợ tổng hợp và đề xuất lựa chọn trong phiên này. Chưa có biên bản pitch/challenge thực tế: không gán câu hỏi cho thành viên và không coi điểm số đề xuất là điểm nhóm đã thống nhất. Theo RULES.md, nhóm cần tự thực hiện phần pitch và challenge; sau đó cập nhật câu hỏi thật, người hỏi và quyết định cuối.

### 2.1. Pitch — 3 candidate đề xuất của mỗi thành viên

**Nguồn đọc:**

- [Phan Trọng Hậu — CP1, CP2](../individual/2A202603547_PhanTrongHau.md).
- [Ngô Đức Thịnh — CP1, CP2](../individual/2A202603548_NgoDucThinh.md).
- [Đinh Trần Nguyên — CP1, CP2](../individual/03517_DinhTranNguyen.md).
- [Bùi Gia Huy — CP1, CP2](../individual/2A202603525_BuiGiaHuy.md).

|   # | Người đưa ra     | Candidate (Job Story ngắn)                                                                                                                                | Actor                                                 | Bottleneck                                                                                                                                          | Câu hỏi phản biện nhận được (ai hỏi)              |
| --: | ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------- |
|   1 | Phan Trọng Hậu   | Khi bên thứ ba gửi bản tài liệu giao dịch mới, tôi muốn biết các điều khoản và số liệu đã đổi, để chuyển đúng nội dung cần rà soát trước giao dịch.       | Kế toán/admin; các bạn admin đã nêu pain với Hậu      | Đối chiếu ý nghĩa thay đổi với checklist: 20 phút/cặp, **ước lượng**; tổng 50 phút cũng chưa đo                                                     | Chưa ghi nhận câu hỏi/người hỏi trong buổi pitch. |
|   2 | Phan Trọng Hậu   | Khi bộ nhớ gần đầy, tôi muốn lọc ảnh trùng và ảnh không còn cần, để có chỗ lưu mà không xóa nhầm ảnh quan trọng.                                          | Dương, bạn gái Hậu, đã nêu pain về dung lượng         | So sánh ảnh để chọn ảnh xóa/giữ: 15 phút/100 ảnh, **ước lượng**; tổng 40 phút chưa đo                                                               | Chưa ghi nhận câu hỏi/người hỏi trong buổi pitch. |
|   3 | Phan Trọng Hậu   | Khi phải vào nhiều nền tảng làm việc, tôi muốn xử lý thông tin cần thiết mà không bị cuốn sang nội dung khác, để không nhỡ tin quan trọng ở kênh còn lại. | Hậu, người phải dùng nhiều nền tảng cho công việc     | Bị cuốn khỏi việc chính: 20 phút/phiên, **ước lượng**; chưa có log hoặc tần suất                                                                    | Chưa ghi nhận câu hỏi/người hỏi trong buổi pitch. |
|   4 | Ngô Đức Thịnh    | Khi ứng tuyển nhiều nơi, tôi muốn diễn đạt kinh nghiệm thật phù hợp từng JD, để chuẩn bị đúng CV và hạn chế gửi nhầm.                                     | Sinh viên tìm thực tập/người tìm việc                 | Viết lại mô tả kinh nghiệm: nguồn CP2 ghi 20 phút/CV, tổng chuẩn bị 30 phút; chưa có log đính kèm                                                   | Chưa ghi nhận câu hỏi/người hỏi trong buổi pitch. |
|   5 | Ngô Đức Thịnh    | Khi đọc tiếng Anh, tôi muốn lưu và ôn từ đã tra cùng câu gốc, để nhớ cách dùng trong ngữ cảnh.                                                            | Người học ngoại ngữ, sinh viên đọc tài liệu tiếng Anh | Chuyển tab, ghi từ/nghĩa/câu gốc: nguồn CP2 ghi 2–3 phút/từ; cần đo lại, chưa dùng tỷ lệ “quên 80%” như số liệu đã kiểm                             | Chưa ghi nhận câu hỏi/người hỏi trong buổi pitch. |
|   6 | Ngô Đức Thịnh    | Khi thông báo trường nằm ở nhiều kênh, tôi muốn nhận ra tin liên quan khóa/ngành mình, để không bỏ lỡ hạn hoặc thay đổi lịch.                             | Sinh viên theo dõi thông báo học tập                  | Rà 4 kênh mỗi ngày; CP1 kể từng trễ hạn khi tin trôi sau 100+ tin nhắn, chưa có số phút riêng                                                       | Chưa ghi nhận câu hỏi/người hỏi trong buổi pitch. |
|   7 | Đinh Trần Nguyên | Khi chuẩn bị nộp lab, tôi muốn đối chiếu đủ yêu cầu rubric và checkpoint, để không bỏ sót bài hoặc mục bắt buộc.                                          | Sinh viên nộp bài lab                                 | Đọc/đối chiếu yêu cầu với bài: tổng kiểm khoảng 15–20 phút **ước tính**, chưa tách bước; nguồn kể từng phát hiện thiếu bài sau deadline             | Chưa ghi nhận câu hỏi/người hỏi trong buổi pitch. |
|   8 | Đinh Trần Nguyên | Khi gặp kiến thức chưa rõ lúc làm lab, tôi muốn tìm đúng file/trang slide, để đọc lại và áp dụng vào bài.                                                 | Người học/AI Developer                                | Tìm nội dung trong slide khoảng 30 phút **ước tính**; nguồn kể một lần tổng đọc và thực hành khoảng 120 phút, không quy toàn bộ thành thời gian tìm | Chưa ghi nhận câu hỏi/người hỏi trong buổi pitch. |
|   9 | Đinh Trần Nguyên | Khi nhận user story, tôi muốn hiểu rõ description và DoD, để bắt đầu làm mà không phải dừng hỏi PM.                                                       | Thành viên nhận task; PM bổ sung yêu cầu              | Hỏi và chờ bổ sung khoảng 10 phút **ước tính**, gộp bước 3–4; nguồn ghi đã quan sát một lần, chưa rõ tần suất                                       | Chưa ghi nhận câu hỏi/người hỏi trong buổi pitch. |
|  10 | Bùi Gia Huy      | Khi chuẩn bị đi học, tôi muốn biết đúng ca/phòng và giờ xuất phát, để không dò lịch lặp lại hoặc lỡ chuyến buýt.                                          | Huy, học viên đi học bằng xe buýt                     | Nguồn ghi khoảng 5 phút tra cứu; nếu lệch chuyến chờ thêm 10–15 phút. Tách khỏi 20 phút di chuyển vốn không phải thời gian có thể loại bỏ           | Chưa ghi nhận câu hỏi/người hỏi trong buổi pitch. |
|  11 | Bùi Gia Huy      | Khi bắt đầu lab mới, tôi muốn nắm yêu cầu và tiêu chí rải ở nhiều file, để bắt đầu đúng trọng tâm.                                                        | Học viên nhận repo lab                                | Đọc và đối chiếu nhiều file, nguồn CP1/CP2 ghi 15–20 phút; cần thống nhất với sơ đồ cộng hai bước đọc thành khoảng 20 phút                          | Chưa ghi nhận câu hỏi/người hỏi trong buổi pitch. |
|  12 | Bùi Gia Huy      | Khi lớp có thông báo đổi phòng/lịch hoặc hạn nộp, tôi muốn tìm đúng tin mới nhất, để không dùng thông tin cũ hay bỏ lỡ hạn.                               | Học viên lớp K5-L3A                                   | Lướt tìm tin giữa thảo luận: nguồn ghi 5–10 phút/ngày; sơ đồ còn thêm 5 phút đối chiếu lịch, cần đo lại cùng phạm vi                                | Chưa ghi nhận câu hỏi/người hỏi trong buổi pitch. |

### 2.2. Cluster

Các cluster gom theo nhu cầu, chưa gộp mọi actor thành một bài toán rộng. Mã candidate tham chiếu bảng 2.1.

| Cluster                                               | Các candidate                                                                                   | Pattern chung                                                                                                                                             |
| ----------------------------------------------------- | ----------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| A — Kiểm soát yêu cầu và thay đổi trước khi hành động | #1 tài liệu bên thứ ba; #7 kiểm bài; #9 task thiếu DoD; #11 hiểu yêu cầu lab                    | Phải xác định đúng nội dung cần tuân thủ, nội dung còn thiếu hoặc đã đổi. #7 và #11 liên quan nhưng khác thời điểm: trước nộp so với đầu buổi.            |
| B — Nhận đúng thông tin khi cần                       | #3 công việc nhiều nền tảng; #6 thông báo trường; #10 lịch học/giờ xuất phát; #12 thông báo lớp | Thông tin cần hành động nằm giữa nhiều kênh hoặc thao tác tra cứu. #6 và #12 gần trùng; #3 có nguyên nhân thêm là bị cuốn khỏi công việc, cần kiểm riêng. |
| C — Tái sử dụng kiến thức và kinh nghiệm cá nhân      | #4 CV/JD; #5 từ vựng theo ngữ cảnh; #8 tìm slide                                                | Nội dung đã có nhưng mất công tìm lại, chọn và vận dụng cho tình huống hiện tại; không mặc định chung một giải pháp.                                      |
| D — Giải phóng dung lượng mà giữ được ảnh quan trọng  | #2 dọn ảnh                                                                                      | Cần phân biệt ảnh thực sự dư với ảnh còn giá trị; đo bằng công dọn và dung lượng thu hồi. Không ép vào cluster học tập chỉ để giảm số nhánh.              |

### 2.3. Opportunity Solution Tree rút gọn

Outcome chung đề xuất ở vòng mở rộng: **Giảm thời gian xử lý thông tin trước khi hành động mà không tăng bỏ sót thông tin hoặc mất dữ liệu quan trọng.** Khi chọn candidate, phải thu hẹp outcome về một actor và một quy trình; outcome chung này chưa phải success metric.

```text
OUTCOME: Giảm thời gian xử lý thông tin mà không tăng bỏ sót/mất dữ liệu quan trọng
├── A. Hiểu đúng yêu cầu, nhận ra nội dung thiếu hoặc thay đổi trước khi hành động
│   ├── Kiểm soát bản tài liệu bên thứ ba cập nhật (#1)
│   ├── Biết bài làm còn thiếu yêu cầu nào (#7, #11)
│   └── Nhận task đủ thông tin để bắt đầu (#9)
├── B. Tiếp cận thông tin cần hành động đúng lúc
│   ├── Không bị cuốn khỏi công việc khi mở các nền tảng (#3)
│   ├── Không để thông báo quan trọng trôi giữa tin nhắn (#6, #12)
│   └── Biết đúng lịch/phòng và giờ cần xuất phát (#10)
├── C. Tìm và vận dụng nội dung đã có đúng ngữ cảnh
│   ├── Trình bày kinh nghiệm thật phù hợp vị trí ứng tuyển (#4)
│   ├── Nhớ và dùng lại từ đã gặp (#5)
│   └── Tìm đúng phần kiến thức để thực hành (#8)
└── D. Có đủ dung lượng lưu ảnh mà giữ được ảnh quan trọng (#2)
```

**Diễn đạt thiên về solution được loại khỏi tên opportunity trong bản tổng hợp:**

- “Tự động trích xuất/cập nhật lịch” → nhu cầu nhận ra thông báo mới và đúng thời điểm; cách tự động hóa xét sau.
- “Checklist tương tác”, “audio tóm tắt”, “bot tổng hợp” → là phương án, không phải pain để đặt làm nhánh OST.
- “AI xác định review thật/giả” → chưa có chuẩn kiểm chứng; không đưa vào shortlist chỉ vì nghe phù hợp AI.

Đây là chỉnh cách diễn đạt khi tổng hợp, không phải ghi nhận nhóm đã nêu rồi gạch bỏ trong một buổi thảo luận thật.

### 2.4. Chấm điểm shortlist (1–5)

**Shortlist đề xuất:** #7 kiểm bài theo rubric, #1 kiểm soát tài liệu bên thứ ba và #2 dọn ảnh. Ba candidate có đầu vào/đầu ra có thể kiểm tra và đại diện cho các mức độ bằng chứng, tiếp cận domain khác nhau. Các candidate còn lại vẫn nằm trong danh sách, không bị loại vì không cần AI.

**Cách hiểu điểm:** 1 = chưa rõ/rất thiếu; 3 = đã mô tả được nhưng còn cần kiểm; 5 = rõ, có cơ sở trực tiếp và phạm vi hẹp. “Pain có bằng chứng” dựa trên lời kể/ghi chép hiện có, không coi ước lượng là đo thật. “Nhóm hiểu domain” mới là đánh giá khả năng tiếp cận thể hiện qua báo cáo, chưa phải xác nhận của cả nhóm. Tất cả điểm dưới là đề xuất phân tích, chưa phải điểm nhóm tự chấm.

| Candidate                              | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
| -------------------------------------- | -------: | -----------: | -----------------: | -------------: | ----------: | -------------------------------------: | ---------------: | ---: |
| #7 — Nguyên: kiểm bài theo rubric      |        5 |            4 |                  3 |              4 |           5 |                                      5 |                4 |   30 |
| #1 — Hậu: tài liệu bên thứ ba cập nhật |        5 |            4 |                  3 |              4 |           3 |                                      5 |                2 |   26 |
| #2 — Hậu: dọn ảnh cho Dương            |        5 |            4 |                  3 |              4 |           4 |                                      5 |                3 |   28 |

**Giải thích điểm quyết định:**

- Cả ba có điểm bằng chứng 3: có nguồn pain được kể lại, nhưng chưa có log, mẫu xử lý và baseline đo thật. #7 có một sự cố thiếu bài sau deadline; #1 do admin nêu với Hậu; #2 do Dương nêu với Hậu. Không nâng điểm chỉ vì có số phút ước lượng trong card.
- #7 vừa sức hơn vì có đề bài, rubric, báo cáo trong repo và người học dễ tiếp cận. Quy trình mới 4 vì chưa tách thời gian từng bước; hiểu domain 4 vì các thành viên có trải nghiệm học tập, chưa xác nhận đồng thuận.
- #1 actor rõ nhưng còn thiếu cặp tài liệu được phép dùng, checklist và người có thẩm quyền rà; do đó vừa sức 3, hiểu domain 2. Điểm thấp hơn phản ánh điều kiện lab hiện tại, không khẳng định pain ít giá trị hơn.
- #2 có mẫu ảnh dễ mô tả nhưng chưa xác nhận Dương cung cấp bộ ảnh hay vị trí thiếu dung lượng; ảnh rác phụ thuộc sở thích. Vừa sức 4, hiểu domain 3; cần kiểm an toàn khi xóa.
- Cả ba so sánh được các mức can thiệp (5): checklist/so sánh văn bản/Rule tìm file trùng là đối chứng rõ; không cần chọn Agent để đạt điểm này.

**Candidate được chọn:** **Đề xuất #7 — Sinh viên kiểm tra bài lab với rubric/checkpoint trước nộp để tránh bỏ sót yêu cầu bắt buộc. Chờ nhóm tự chốt sau pitch và challenge.**

**Vì sao đề xuất:** Điểm cao nhất trong shortlist theo dữ liệu hiện có; đã có một hậu quả cụ thể được kể, có vật liệu thử ngay trong repo và thuận lợi hỏi người học khác ở CP4. Phạm vi ban đầu chỉ một bài lab, danh sách yêu cầu và các vị trí bằng chứng tương ứng trong bài làm; không tự chấm chất lượng toàn bộ bài hoặc bảo đảm điểm. Chưa quyết định dùng AI: phải so với checklist và Rule kiểm file trước.

**Vì sao chưa chọn các candidate còn lại:**

- #1 tài liệu bên thứ ba: giá trị tiềm năng rõ, nhưng chưa xác nhận quyền dùng mẫu, checklist kiểm soát và người rà domain. Nếu nhóm có đủ ba điều kiện này, cần chấm lại; đây có thể trở thành candidate ưu tiên.
- #2 dọn ảnh: có người nêu pain nhưng thiếu mục tiêu dung lượng, bộ ảnh thật và tiêu chí ảnh rác do Dương xác nhận. Nên kiểm trước liệu lọc file giống hệt và dọn thủ công đã đủ.
- #6/#12 thông báo: có thể gom một candidate sau pitch, nhưng cần tập tin nhắn được phép dùng và cách xác định thông báo chuẩn. Không coi AI phân loại là bằng chứng không bỏ sót.
- #3 nhiều nền tảng: pain đã được Hậu mô tả nhưng giải pháp lấy nguồn chưa rõ; chỉ tổng hợp dữ liệu người dùng phải tự chép có thể không giảm xao nhãng.
- #4 CV, #5 từ vựng, #8 tìm slide: đều có thể thử, nhưng cần làm rõ chất lượng đầu ra và phép đo riêng; không dùng tỷ lệ quên từ hoặc qua vòng CV chưa kiểm chứng để tăng điểm.
- #9 DoD và #10 lịch học: template/quy định giao việc hoặc lịch nhắc có thể là đối chứng rất mạnh. Kết luận No AI/Rule vẫn hợp lệ, nhưng hiện chưa có bằng chứng lợi ích hơn candidate đề xuất.
- #11 đọc yêu cầu lab: giữ làm pain liên quan của #7; chưa gộp thời gian đọc ban đầu và kiểm trước nộp thành một baseline.

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| Giả định cần kiểm chứng                                                                          | Loại        | Quan trọng (1–5) | Bằng chứng (1–5) |
| ------------------------------------------------------------------------------------------------ | ----------- | ---------------- | ---------------- |
| Nhiều học viên gặp khó khăn khi hiểu yêu cầu nằm trong nhiều file tài liệu lab.                  | Value       | 3                | 2                |
| Việc hiểu thiếu yêu cầu lab có thể dẫn đến bỏ sót nội dung bắt buộc khi nộp bài.                 | Value       | 5                | 2                |
| Học viên có thể xác định yêu cầu còn thiếu khi được chỉ rõ nội dung và nguồn tài liệu liên quan. | Usability   | 4                | 1                |
| Nhóm có thể truy cập đầy đủ tài liệu lab cần thiết để đối chiếu yêu cầu với bài làm.             | Feasibility | 3                | 2                |
| Quy trình kiểm tra yêu cầu có thể thực hiện trong thời gian chấp nhận được trước deadline.       | Viability   | 2                | 2                |

Giả định nhóm kiểm chứng trong buổi này: Việc hiểu thiếu yêu cầu lab có thể dẫn đến bỏ sót nội dung bắt buộc khi nộp bài.
                                                                       |

### 3.2. Kiểm chứng

**Cách đã dùng:** Phỏng vấn (dữ liệu giả lập để minh họa).

**Interview snapshot 1**

| Trường                                            | Nội dung                                                                                                                                                                      |
| ------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Người được hỏi (vai trò, không ghi tên thật)      | P1 – Học viên tham gia Coding Lab                                                                                                                                             |
| Câu nói đáng nhớ nhất (nguyên văn)                | "Em tưởng chỉ cần code chạy được, đến lúc xem lại rubric mới biết còn phải ghi kết quả đánh giá vào báo cáo."                                                                 |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Trong một bài lab về Machine Learning, P1 hoàn thành code nhưng bỏ sót phần giải thích kết quả vì chưa hiểu đầy đủ yêu cầu trong rubric. P1 chỉ phát hiện sau khi đã nộp bài. |
| Hiện đang xử lý bằng cách nào (workaround)?       | Đọc lại README và rubric, tự lập checklist những phần cần hoàn thành trước khi nộp.                                                                                           |
| Mất bao lâu, bao lần?                             | Ước tính 15–20 phút kiểm tra mỗi bài lab. Từng gặp 2 lần hiểu thiếu yêu cầu.                                                                                                  |
| Insight / opportunity rút ra                      | Học viên có thể hoàn thành phần kỹ thuật nhưng vẫn bỏ sót yêu cầu báo cáo. Cần giúp học viên đối chiếu từng yêu cầu với sản phẩm đầu ra.                                      |

**Interview snapshot 2**

| Trường                                            | Nội dung                                                                                                                                                                                                     |
| ------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Người được hỏi (vai trò, không ghi tên thật)      | P2 – Học viên tham gia Coding Lab                                                                                                                                                                            |
| Câu nói đáng nhớ nhất (nguyên văn)                | "Có nhiều file hướng dẫn nên đôi lúc em không biết phải ưu tiên kiểm tra file nào trước."                                                                                                                    |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Khi thực hiện bài lab nhóm, P2 đọc README nhưng không chú ý một yêu cầu bổ sung trong CHECKPOINTS. Tuy nhiên, P2 phát hiện phần còn thiếu khi đối chiếu bài làm với checklist trước deadline và kịp bổ sung. |
| Hiện đang xử lý bằng cách nào (workaround)?       | Tổng hợp yêu cầu từ các file Markdown vào một checklist chung, đánh dấu từng mục đã hoàn thành.                                                                                                              |
| Mất bao lâu, bao lần?                             | Khoảng 10–15 phút tổng hợp và kiểm tra yêu cầu mỗi bài. Ghi nhận 1 lần hiểu thiếu nhưng sửa kịp trước khi nộp.                                                                                               |
| Insight / opportunity rút ra                      | Hiểu thiếu yêu cầu không phải lúc nào cũng dẫn đến bỏ sót khi nộp. Checklist có thể là biện pháp phòng tránh hiệu quả mà không cần AI.                                                                       |

### Interview snapshot 3

| Trường                                            | Nội dung                                                                                                                                                                                                                                     |
| ------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Người được hỏi (vai trò, không ghi tên thật)      | P3 – Học viên tham gia Coding Lab                                                                                                                                                                                                            |
| Câu nói đáng nhớ nhất (nguyên văn)                | "Em đọc README thấy một cách đặt tên repo, nhưng trong file hướng dẫn nộp bài lại ghi khác nên không biết phải làm theo cái nào."                                                                                                            |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Khi chuẩn bị nộp bài lab, P3 nhận thấy quy định đặt tên repository trong README và SUBMISSION chưa thống nhất. P3 phải đọc lại các tài liệu và hỏi người hướng dẫn để xác định quy định cần áp dụng.                                         |
| Hiện đang xử lý bằng cách nào (workaround)?       | Đối chiếu các file hướng dẫn, hỏi người hướng dẫn hoặc trợ giảng khi phát hiện thông tin mâu thuẫn.                                                                                                                                          |
| Mất bao lâu, bao lần?                             | Khoảng 10–15 phút để kiểm tra và xác nhận lại. Ghi nhận 1 lần gặp tình huống này (giả lập).                                                                                                                                                  |
| Insight / opportunity rút ra                      | Khó khăn không chỉ đến từ việc học viên hiểu thiếu yêu cầu mà còn từ thông tin chưa thống nhất giữa các tài liệu. Cần giúp học viên phát hiện những yêu cầu mâu thuẫn và xác định nguồn cần được xác nhận, thay vì tự lựa chọn một quy định. |

**Tổng hợp:**

| Nguồn                                   | Số người / số mẫu | Tín hiệu xác nhận                                                                                                                                   | Tín hiệu phản bác                                                                                                |
| --------------------------------------- | ----------------: | --------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| Phỏng vấn học viên Coding Lab (giả lập) |                 3 | P1 bỏ sót nội dung do hiểu thiếu rubric. P2 gặp khó khăn vì yêu cầu nằm ở nhiều file. P3 gặp thông tin chưa thống nhất giữa các tài liệu hướng dẫn. | P2 phát hiện và sửa kịp nhờ checklist. P3 chưa xác nhận việc mâu thuẫn tài liệu dẫn đến bỏ sót nội dung khi nộp. |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

Từ các tình huống giả lập, nhóm đề xuất mở rộng nguyên nhân của vấn đề: học viên không chỉ có nguy cơ bỏ sót yêu cầu do hiểu thiếu, mà còn gặp khó khăn khi yêu cầu phân tán hoặc chưa thống nhất giữa nhiều tài liệu.

**Problem được đề xuất điều chỉnh:**

"Học viên Coding Lab cần đọc và đối chiếu yêu cầu từ nhiều tài liệu như README, CHECKPOINTS, RUBRIC và SUBMISSION. Khi các yêu cầu nằm rải rác, khó hiểu hoặc chưa thống nhất, học viên có thể mất thêm thời gian xác minh, hiểu sai hoặc bỏ sót nội dung bắt buộc khi nộp bài."

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern                       | Link                                                                                                      | Giải bước nào trong quy trình?                                                                                                  | Điểm mạnh                                                                                                                        | Khoảng trống / rủi ro                                                                                                                                              | Bài học cho nhóm                                                                                                                                                            |
| ---------------------------------------------- | --------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| GitHub Markdown Task Lists (No AI)             | https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/about-tasklists | Tổng hợp yêu cầu từ README, CHECKPOINTS, RUBRIC thành checklist; đánh dấu hoàn thành trước khi nộp.                             | Đơn giản, miễn phí, dễ áp dụng ngay trong GitHub; giúp học viên theo dõi yêu cầu còn thiếu.                                      | Checklist phải được tạo và cập nhật thủ công; đánh dấu hoàn thành không chứng minh học viên đã hiểu hoặc thực hiện đúng yêu cầu.                                   | Cần có danh sách yêu cầu rõ ràng và cơ chế đối chiếu từng yêu cầu với bằng chứng hoàn thành. Nên thử checklist thủ công làm baseline trước khi áp dụng AI.                  |
| Google NotebookLM (AI hỗ trợ tra cứu tài liệu) | https://support.google.com/gemininotebook/answer/16215270                                                 | Đọc, tổng hợp và giải thích yêu cầu từ nhiều tài liệu; hỗ trợ học viên tìm lại nguồn yêu cầu khi chưa hiểu rõ.                  | Hỗ trợ tài liệu Markdown, PDF và nhiều định dạng khác; trả lời dựa trên nguồn được cung cấp, có trích dẫn để người học kiểm tra. | Phụ thuộc vào độ đầy đủ và phiên bản của tài liệu đã tải lên; câu trả lời AI vẫn cần đối chiếu với nguồn gốc; không tự xác minh toàn bộ bài làm đã đáp ứng rubric. | Nếu sử dụng AI, mỗi yêu cầu được trích xuất cần kèm nguồn tham chiếu. AI chỉ hỗ trợ giải thích và đối chiếu, không tự kết luận bài nộp đạt yêu cầu.                         |
| GitHub Actions (Rule-based Automation)         | https://docs.github.com/en/actions/concepts/workflows-and-actions/workflows                               | Kiểm tra tự động một số điều kiện trước hoặc sau khi đẩy bài lên repository, ví dụ: file bắt buộc, cấu trúc thư mục, test code. | Có thể chạy script kiểm tra tự động theo sự kiện GitHub; kết quả kiểm tra nhất quán với các quy tắc đã định nghĩa.               | Cần viết và duy trì quy tắc; khó đánh giá yêu cầu mang tính ngữ nghĩa như chất lượng giải thích, phân tích hoặc mức độ hiểu rubric.                                | Tách yêu cầu thành hai nhóm: yêu cầu có thể kiểm tra bằng rule và yêu cầu cần con người/AI hỗ trợ đánh giá. Không nên dùng AI cho các kiểm tra đơn giản có thể viết script. |

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text
[1. Gom yêu cầu của bài] (4p)
(Đề bài + Rubric + Chat lớp)
            │
            ▼
[2. Kiểm tra cấu trúc & file] (3p)
(Dò ô trống, dòng mẫu, link ảnh)
            │
            ▼
[3. Đọc dò nội dung theo Rubric] (7p) ⚠️ BOTTLENECK CHÍNH
(So từng ô xem đủ số liệu, đúng chuẩn chưa)
            │
            ▼
[4. Tự sửa các mục bị thiếu/sai] (3p)
            │
            ▼
[5. Commit & Bấm nộp] (1p)
```

| Bước | Actor    | Input                                                                                      | Output                                                                                    | Thời gian / tần suất                | Ghi chú                                                                                     |
| ---: | -------- | ------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------- | ----------------------------------- | ------------------------------------------------------------------------------------------- |
|    1 | Học viên | Trang đề bài gốc, bảng Rubric cuối bài, tin nhắn dặn thêm của giảng viên trên Discord/Zalo | Danh sách các yêu cầu nhớ tạm trong đầu hoặc ghi nháp                                     | 4 phút / mỗi lần nộp (1–2 lần/tuần) | Yêu cầu nằm rải rác ở 3 nơi nên rất dễ quên các dặn dò bổ sung ngoài luồng.                 |
|    2 | Học viên | File bài làm và thư mục                                                                    | Phát hiện các ô bảng bị bỏ trống, dòng mẫu chưa xóa hoặc thiếu file ảnh đính kèm          | 3 phút / mỗi lần nộp                | Cuộn trang bằng mắt lúc khuya (23h) nên hay nhìn sót chữ gợi ý in nghiêng của template.     |
|    3 | Học viên | Nội dung đã viết trong file `.md` + Tiêu chí chấm từng Checkpoint (CP1–CP5)                | Danh sách các chỗ viết chưa đạt chuẩn Rubric (thiếu con số, dính solution vào problem...) | 7 phút / mỗi lần nộp                | Nút thắt lớn nhất: Mở chia đôi màn hình đọc dò từng dòng rất mỏi mắt, dễ đọc lướt cho xong. |
|    4 | Học viên | Danh sách các lỗi/thiếu sót vừa tự tìm ra ở Bước 2 & 3                                     | File bài làm (`.md`) và thư mục tài nguyên đã được bổ sung đầy đủ                         | 3 phút / mỗi lần nộp                | Chỉ sửa được những lỗi mà mắt thường đã phát hiện ra ở bước trước.                          |
|    5 | Học viên | Bộ file bài làm hoàn chỉnh                                                                 | Bài nộp thành công trên GitHub / LMS trước giờ đóng form                                  | 1 phút / mỗi lần nộp                | Vẫn thường xuyên phát hiện sót mục sau khi đã bấm nộp (4/12 bài phải commit bù).            |

**Bottleneck chính:** Nằm ở Bước 2 & Bước 3 (mất tổng cộng 10 phút/lần nộp): Sinh viên phải tự cuộn đọc đối chiếu bằng mắt giữa file bài làm dài với hàng chục tiêu chí nhỏ trong Rubric và các Checkpoint lúc sát giờ deadline (22h–23h59). Khi mệt mỏi và vội vàng, mắt người chỉ nhận biết được "ô đó đã có chữ" chứ rất dễ bỏ sót lỗi "chưa xóa dòng thừa của template", "quên đính kèm file".

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text
[1. Con người: Đưa file bài làm (.md) + Chọn bài Lab/Rubric] (30 giây)
                                │
                                ▼
[2. RULE (Tự động): Quét cấu trúc & cú pháp cứng] (5 giây)
   ├─ Kiểm tra đủ các thẻ tiêu đề lớn (## CP1 -> CP5)
   ├─ Bắt các ô bảng đang bỏ trống (|   |) hoặc còn nguyên chữ mẫu (template)
   └─ Kiểm tra đường dẫn file/ảnh trong `report/assets/` có tồn tại thật không
                                │
                                ▼
[3. AI WORKFLOW (Tự động): Đối chiếu ngữ nghĩa từng mục với Rubric] (15 giây)
   ├─ Kiểm tra từng dòng đã có con số định lượng / bằng chứng theo yêu cầu chưa
   ├─ Phát hiện lỗi tư duy (VD: viết Solution vào ô Job Story / Opportunity)
   └─ Xuất bảng "Pre-submit Report": [✅ Đạt] / [❌ Thiếu - Cần sửa] / [⚠️ Cảnh báo] kèm số dòng
                                │
   ================ BOUNDARY (Ranh giới kiểm soát) ================
   (Hệ thống CHỈ chỉ ra vị trí lỗi & lý do; KHÔNG tự ý viết thêm hay sửa đè vào file bài làm)
                                │
                                ▼
[4. Con người: Xem các dòng gắn cờ ❌/⚠️, tự sửa bài & Bấm nộp] (2 phút)
   └─ (Fallback khi AI báo sai: Xem trích dẫn tiêu chí gốc bên cạnh để tự bỏ qua cờ cảnh báo)
```

Phân vai chi tiết:

Con người (Bước 1 & Bước 4): Tải/chọn file bài làm .md cần kiểm tra (Bước 1); đọc bảng báo cáo lỗi, tự quyết định chỉnh sửa nội dung bài làm của mình và bấm nộp bài (Bước 4).

Rule-based (Bước 2): Dùng biểu thức chính quy (Regex) và kịch bản kiểm tra cú pháp (Markdown parser) để bắt các lỗi cơ học 100% chính xác: thiếu đề mục bắt buộc, ô bảng rỗng, còn sót dòng chữ hướng dẫn mẫu (ví dụ: *Điền 4–6 giả định; xóa dòng thừa.*), hoặc link ảnh dẫn tới file không tồn tại trong thư mục.

AI Workflow (Bước 3): Nhận những phần đã qua bước Rule, đối chiếu từng mục với tiêu chí ngữ nghĩa của Rubric và trả về bảng kết quả ngắn gọn theo từng dòng.

Boundary (Ranh giới an toàn):

Hệ thống dừng lại ở việc xuất báo cáo kiểm tra (Read-only Audit Report) chỉ rõ dòng nào thiếu gì.

Tuyệt đối không dùng Agent tự động viết hộ nội dung còn thiếu vào bài lab hay tự động commit/nộp bài thay sinh viên.

Phương án quay về (Fallback) khi AI sai:

Nếu AI hiểu nhầm ngữ cảnh và báo cảnh báo sai (False Positive): Trên bảng kết quả luôn hiển thị kèm câu trích dẫn nguyên văn từ bài làm của sinh viên đặt cạnh tiêu chí gốc của Rubric để sinh viên nhìn lướt trong 5 giây và bấm nút "Bỏ qua cảnh báo này (Ignore)".

Nếu API của AI bị lỗi/quá tải sát giờ deadline (23h55): Hệ thống vẫn trả về ngay kết quả của Bước 2 (Rule-based Check) kèm danh sách Checklist rút gọn của Rubric để sinh viên dò nhanh các mục đã được khoanh vùng.
### 4.3. Before / after

| Chỉ số               | Trước | Sau (kỳ vọng) | Ghi chú |
| -------------------- | ----: | ------------: | ------- |
| Số bước | 5 bước | **3 bước** (Tính theo thao tác của con người) | Bước 2 (Rule) và Bước 3 (AI) gộp thành 1 lần bấm nút chạy tự động (mất ~20 giây). |
| Tổng thời gian | 15–20 phút (Trung bình **18 phút**/lần) | **~2,5 – 3 phút**/lần | Giảm ~85% thời gian rà soát trước khi nộp (20 giây máy quét + 2 phút người tự sửa lỗi). |
| Số bước thủ công | **5/5 bước** (100% thủ công) | **2 bước** (Đưa file vào & Tự sửa chỗ bị báo thiếu) | Loại bỏ hoàn toàn việc phải mở chia đôi màn hình để đọc dò bằng mắt từ đầu đến cuối. |
| Bottleneck chính | Đọc dò chéo bằng mắt giữa bài làm và Rubric (**10 phút**, dễ sót lỗi nhỏ lúc mệt) | Đọc và tự viết bổ sung các ý bị báo thiếu ở Bước 4 (**~2 phút**) | Áp lực tìm lỗi được chuyển cho máy; con người chỉ tập trung sửa đúng những dòng bị gắn cờ ❌/⚠️. |
| Rủi ro mới phát sinh | *(Không có rủi ro công nghệ, nhưng tỷ lệ sót mục sau deadline là 4/12 bài)* | 1. **AI báo thiếu nhầm (False Positive)** hoặc **bỏ lọt lỗi ngữ nghĩa tinh vi (False Negative)**.<br>2. **Tâm lý ỷ lại:** Sinh viên chỉ sửa các dòng máy báo đỏ mà không đọc lại mạch văn chung. | Khắc phục bằng cách dùng **Rule** bắt cứng các lỗi cấu trúc/bỏ trống trước (độ chính xác 100%) và hiển thị trích dẫn tiêu chí gốc bên cạnh nhận xét của AI. |

---

## 5. Problem Statement v0 (CP5)

| Trường                                                                     | Nội dung |
| -------------------------------------------------------------------------- | -------- |
| **Actor** | học viên nộp bài lab |
| **Quy trình** | 1. Gom yêu cầu từ đề bài, rubric và tin nhắn lớp (4p) → 2. Kiểm tra cấu trúc thư mục, tên file, ô rỗng, dòng template thừa (3p) → 3. Đọc dò chéo nội dung file bài làm `.md` với từng tiêu chí của Rubric (7p) → 4. Tự sửa các mục thiếu sót (3p) → 5. Nộp bài (1p). |
| **Bottleneck** | **Bước 3 (Đọc dò nội dung theo Rubric - mất 7 phút/lần) và Bước 2:** Việc phải cuộn đọc chéo bằng mắt giữa file báo cáo dài và hàng chục tiêu chí nhỏ trong Rubric lúc nửa đêm (sát giờ deadline) khiến mắt mỏi, dễ bỏ sót lỗi nhỏ (thiếu con số định lượng, sót chữ mẫu) hoặc quên các dặn dò ngoài luồng của giảng viên. |
| **Impact** | Tốn trung bình **15–20 phút/lần nộp** chỉ để rà soát thủ công; thường xuyên để lọt các lỗi nhỏ dẫn đến bị trừ điểm oan (0,5–1,5 điểm) hoặc phải commit bổ sung, nộp lại sau deadline (4/12 bài bị sót). |
| **Success Metric** (baseline → target, cách đo) | • **Tổng thời gian rà soát trước khi nộp:** 18 phút → Dưới 3 phút/lần.<br>• **Tỷ lệ sót mục / lỗi cấu trúc sau khi nộp:** 4/12 bài → 0 bài.<br>*(Cách đo: Bấm giờ thực tế thao tác của người dùng từ lúc bấm chạy pre-check đến lúc bấm nộp, và đếm số lỗi phát sinh sau deadline).* |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | • **AI không được:** Tự ý viết bổ sung nội dung còn thiếu vào file bài làm, không tự động commit hay bấm nộp thay sinh viên.<br>• **Con người kiểm tra (HITL):** Toàn bộ báo cáo lỗi (`Report`) do hệ thống Rule + AI trả về chỉ mang tính chất cảnh báo (Read-only); sinh viên phải tự xem xét từng dòng bị gắn cờ ❌/⚠️, tự quyết định chỉnh sửa bài làm của mình và tự bấm nút nộp. |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:
| Điểm phản biện | Đồng ý? | Đã xử lý / điều chỉnh thế nào |
|---|---|---|
| *"Tại sao không làm hẳn một Agent tự động sửa bài và tự động nộp luôn cho sinh viên để tiết kiệm tuyệt đối thời gian?"* | **Không đồng ý** | Giữ vững **Boundary**: Việc để AI tự sửa nội dung có nguy cơ làm sai lệch ý tưởng cốt lõi của sinh viên, vi phạm liêm chính học thuật hoặc gây ra hiện tượnga AI bịa số liệu (hallucination). Con người bắt buộc phải giữ quyền kiểm soát cuối cùng (Human-in-the-loop). |
| *"Thời gian 18 phút kiểm tra có vẻ cao nếu sinh viên làm bài kỹ từ đầu?"* | **Đồng ý một phần** | Thực tế có những bạn chỉ mất 2–3 phút lướt qua rồi nộp vội, và nhóm này chính là nhóm hay bị sót bài nhất. Do đó, hệ thống Pre-check cần được thiết kế cực kỳ nhanh gọn (~20 giây máy chạy) để ép nhóm "lướt vội" này cũng phải qua một lớp lọc lỗi cơ bản. |
- ***

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô: **Độ phức tạp quy trình THẤP–TRUNG BÌNH (luồng bước cố định) × Độ mơ hồ của dữ liệu từ THẤP (cấu trúc file/bảng) đến CAO (ngữ nghĩa nội dung so với tiêu chí Rubric)** → Thuộc vùng giao thoa giữa **Rule** và **AI Workflow**.

Vì sao:
- **Quy trình kiểm tra trước khi nộp có các bước hoàn toàn xác định trước (Low Process Complexity):** Luôn đi theo thứ tự cố định: *(1) Đọc danh sách yêu cầu từ Rubric/Checkpoints → (2) Kiểm tra cấu trúc/file đính kèm → (3) Đối chiếu nội dung từng mục trong file `.md` → (4) Xuất báo cáo các mục thiếu/chưa đạt*. Quy trình này không cần hệ thống tự lập kế hoạch động hay tự gọi công cụ ngoài phạm vi bài lab.
- **Đầu vào có 2 tầng độ mơ hồ khác nhau:**
  1. **Tầng không mơ hồ (Low Ambiguity):** Kiểm tra đủ thẻ tiêu đề (`##`), ô bảng bị bỏ trống (`|   |`), còn sót câu hướng dẫn mẫu của template, hoặc đường dẫn ảnh trong `report/assets/` có tồn tại hay không → **Rule-based (Regex / Markdown Parser)** giải quyết chính xác 100%.
  2. **Tầng mơ hồ ngữ nghĩa (High Ambiguity):** Đánh giá xem nội dung học viên viết trong ô đã đáp ứng yêu cầu của Rubric chưa (ví dụ: *Success Metric đã có con số `baseline → target` chưa, hay mới viết chung chung "nhanh hơn, tốt hơn"? Job Story có bị lồng giải pháp AI vào không? Hai file hướng dẫn có yêu cầu nào mâu thuẫn nhau không?*) → Các quy tắc cứng (Regex) không hiểu được ngữ nghĩa này, cần **AI Workflow (LLM)** đọc hiểu và đối chiếu theo prompt cố định.

### 6.2. So sánh 4 mức

| Mức                       | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
| ------------------------- | -------------------------- | ---------- | ------ | ----- |
| **No AI** (sửa quy trình) | Tạo sẵn một bảng **Master Checklist tĩnh** (Markdown Task List `- [ ]`) gom toàn bộ yêu cầu từ `README`, `CHECKPOINTS`, `RUBRIC`, `SUBMISSION` vào đầu file báo cáo để học viên tự tích tay trước khi nộp. | Đủ khi bài lab có ít mục, yêu cầu chỉ dừng ở mức "có điền hay chưa", và học viên còn đủ tỉnh táo để tự đọc dò trung thực từng mục. | Học viên tích chọn theo quán tính ("tưởng là đã làm đúng") lúc sát giờ deadline (23h); không phát hiện được lỗi hiểu sai bản chất tiêu chí trong Rubric (như trường hợp của P1 ở CP4). | **Một phần** *(Dùng làm baseline đối chứng trước khi bật AI)* |
| **Rule**                  | Viết script Python / GitHub Action dùng Regex & Markdown Parser quét tự động file `.md`: báo lỗi nếu thiếu heading bắt buộc, còn ô bảng trống, còn sót dòng chữ mẫu in nghiêng của template, sai quy tắc đặt tên file `MSSV_HoTen.md`, hoặc link ảnh gãy. | Đủ để bắt 100% các lỗi cơ học, định dạng và bỏ sót mục trống mà không tốn chi phí API hay sợ AI bịa (hallucination). | Mù ngữ nghĩa: Chỉ biết ô bảng "đã có chữ", nhưng không phân biệt được nội dung đó đã có số liệu định lượng theo Rubric hay chỉ viết đối phó, lạc đề. | **Có — Bước 2** *(Làm lớp lọc cứng đầu tiên)* |
| **Workflow**              | **Pipeline cố định 2 tầng (Rule + LLM Prompt):** Sau khi Rule quét xong phần khung, một chuỗi LLM cố định nhận *(Tiêu chí Rubric + Nội dung từng mục trong `.md`)* để đối chiếu ngữ nghĩa, phát hiện lỗi thiếu baseline/target hoặc lỗi "solution-first", rồi xuất bảng **Pre-submit Audit Report (Read-only)** gắn cờ `✅/❌/⚠️` kèm trích dẫn dòng lỗi. | Đủ khi cần kiểm tra cả cấu trúc cứng lẫn chất lượng/độ khớp ngữ nghĩa của nội dung báo cáo so với Rubric trong thời gian nhanh (~20 giây) và chi phí kiểm soát được. | AI có thể báo lỗi nhầm (False Positive) hoặc bỏ lọt lỗi tinh vi (False Negative); học viên có thể ỷ lại chỉ sửa dòng báo đỏ. *(Kiểm soát được bằng cách đính kèm trích dẫn gốc và giữ quyền quyết định cho con người)*. | **CHỌN CHÍNH** *(Kết hợp Rule + AI Workflow)* |
| **Agent**                 | AI Agent tự động quét toàn bộ repo, tự suy luận chỗ thiếu, **tự viết thêm nội dung vào file báo cáo `.md`**, tự sửa câu chữ cho khớp Rubric và tự chạy lệnh `git commit / git push` nộp bài. | Chỉ phù hợp với các tác vụ sinh mã/tài liệu tự động hoàn toàn trong nội bộ kỹ thuật mà không đánh giá năng lực tư duy cá nhân của người học. | **Rủi ro cực cao & Vi phạm `RULES.md`:** Agent tự viết bài thay học viên sẽ bịa số liệu kiểm chứng, làm mất tư duy cá nhân, vi phạm quy định học thuật và phá vỡ hoàn toàn mục tiêu đào tạo của khóa lab. | **Không chọn** *(Loại bỏ hoàn toàn)* |

**Mức chọn:** **Kết hợp Rule + AI Workflow (Hybrid Rule-first Workflow)** — trong đó **Rule** xử lý kiểm tra cấu trúc/định dạng cứng (Bước 2) và **AI Workflow** xử lý đối chiếu ngữ nghĩa với Rubric để xuất báo cáo cảnh báo Read-only (Bước 3).

**Vì sao không chọn mức đơn giản hơn:**
- Nếu chỉ dừng ở **No AI (Checklist tĩnh)** hoặc **Rule thuần túy**: Chỉ ngăn được lỗi "quên điền ô trống" hoặc "thiếu file", nhưng không giải quyết được **Bottleneck lớn nhất (7 phút ở Bước 3)** và nguyên nhân cốt lõi từ CP4 là học viên *đã viết chữ vào ô nhưng viết thiếu thành phần ngữ nghĩa mà Rubric yêu cầu* (ví dụ: viết Metric nhưng không có con số `baseline → target`, viết phản biện nhưng thiếu câu trả lời đã sửa gì, hoặc không nhận ra sự khác biệt giữa yêu cầu trong `README` và `SUBMISSION`).
- Tuy nhiên, nhóm **tuyệt đối không nhảy lên Agent** vì quy trình kiểm tra là cố định và việc tự động sửa bài làm thay học viên là vi phạm ranh giới đạo đức học tập (Boundary).

### 6.3. AI Canvas rút gọn

| Thành phần                                                        | Nội dung |
| ----------------------------------------------------------------- | -------- |
| **Prediction** — AI dự đoán / tạo ra gì?                          | Đánh giá mức độ đáp ứng của từng mục trong file báo cáo (`.md`) so với từng tiêu chí trong `RUBRIC.md` / `CHECKPOINTS.md`, phân loại thành 3 trạng thái: `✅ Đạt` / `❌ Thiếu thành phần bắt buộc` / `⚠️ Cảnh báo mơ hồ hoặc mâu thuẫn tài liệu`, kèm trích dẫn nguyên văn câu trong bài làm và tiêu chí gốc. |
| **Judgment** — con người cân nhắc, quyết định gì?                 | Học viên đọc các dòng bị gắn cờ `❌/⚠️`, đối chiếu với câu trích dẫn Rubric bên cạnh để phán đoán xem cảnh báo của AI là đúng hay báo nhầm (False Positive), từ đó tự quyết định cách viết bổ sung bằng trải nghiệm thật của mình. |
| **Action** — hành động cuối cùng là gì, ai làm?                   | **Học viên (Con người)** trực tiếp gõ chỉnh sửa nội dung vào file `.md` trên VS Code, kiểm tra lại lần cuối và tự thực hiện lệnh `git commit` & `git push` để nộp bài. |
| **Outcome** — đo kết quả bằng gì?                                 | 1. Giảm thời gian rà soát trước khi nộp từ baseline ước tính **15–20 phút xuống dưới 3 phút/lần**.<br>2. Giảm tỷ lệ bài nộp bị sót mục bắt buộc hoặc sai quy cách cấu trúc từ **4/12 bài xuống 0 bài**. |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Cần 2 đầu vào dạng văn bản Markdown: (1) File bài làm của học viên/nhóm (`report/individual/*.md` hoặc `report/team/group_report.md`) và (2) Bộ file yêu cầu của buổi lab (`README.md`, `CHECKPOINTS.md`, `RUBRIC.md`, `SUBMISSION.md`). **Tất cả đều có sẵn 100% ngay trong repo bài lab.** |
| **Feedback** — lấy phản hồi ở đâu để cải thiện?                   | 1. Ghi nhận thao tác bấm nút *"Bỏ qua cảnh báo (Ignore / Báo nhầm)"* của học viên trên từng dòng để tinh chỉnh lại Prompt/Rule.<br>2. Đối chiếu kết quả chấm điểm thực tế của Giảng viên/TA sau buổi lab xem có lỗi nào học viên bị trừ điểm mà hệ thống Pre-check đã bỏ sót (False Negative) hay không. |

### 6.4. Hai câu hỏi của Google PAIR

- **Người dùng muốn được hỗ trợ (augment) hay giao hẳn việc (automate)? Bằng chứng:**
  - Người dùng cần **được hỗ trợ (Augment)** ở khâu rà soát đối chiếu ngữ nghĩa (và chỉ **Automate** ở khâu quét lỗi cú pháp cơ học bằng Rule), tuyệt đối **không giao hẳn việc viết/sửa bài cho AI**.
  - **Bằng chứng:** Từ CP4 (Interview P1, P2, P3) và quy định tại `RULES.md`, học viên muốn giữ quyền chủ động với nội dung bài làm của mình vì điểm số phụ thuộc vào trải nghiệm cá nhân và bằng chứng thật (AI không thể biết học viên đã hỏi ai hay mất bao nhiêu phút ngoài đời). Hơn nữa, việc AI tự ý sửa đè vào file Markdown rất dễ làm hỏng mạch lập luận hoặc vi phạm quy chế "không dùng AI viết thay". Do đó, một trợ lý chỉ điểm lỗi (*"Mục 5. Success Metric của bạn đang thiếu con số baseline"*) giúp học viên vừa tiết kiệm thời gian dò mắt, vừa hoàn toàn làm chủ bài nộp.

- **AI sai kiểu nào tệ hơn, báo nhầm (False Positive) hay bỏ sót (False Negative)? Vì sao, và thiết kế đã xử lý thế nào:**
  - **Bỏ sót (False Negative) tệ hơn nhiều so với Báo nhầm (False Positive).**
  - **Vì sao:**
    - Nếu AI **báo nhầm (False Positive)** (ví dụ: học viên đã viết số liệu ở câu dưới nhưng AI vẫn cảnh báo *"Có thể thiếu số liệu baseline"*): Học viên chỉ mất **~5–10 giây** nhìn lại dòng trích dẫn đó và bỏ qua cảnh báo, không bị mất điểm.
    - Ngược lại, nếu AI **bỏ sót (False Negative)** (báo `✅ Đạt` trong khi bài làm thực tế đang thiếu một yêu cầu bắt buộc trong Rubric hoặc sai quy tắc trong `SUBMISSION.md`): Học viên sẽ yên tâm bấm nộp ngay và **hậu quả là bị trừ điểm trực tiếp hoặc bài nộp không hợp lệ sau deadline** — không còn cơ hội sửa chữa.
  - **Thiết kế đã xử lý thế nào:**
    1. **Dùng Rule-based chặn trước ở Bước 2:** Toàn bộ các yêu cầu mang tính cấu trúc cứng (tên file, đủ mục, không để ô trống, không còn chữ template mẫu, link ảnh tồn tại) được kiểm tra bằng code Rule với độ nhạy 100% (Zero False Negative cho lỗi cấu trúc).
    2. **Thiết kế ngưỡng nhạy của AI thiên về "Thận trọng (Conservative)":** Bất kỳ mục nào AI không tìm thấy bằng chứng rõ ràng khớp với Rubric sẽ được gắn cờ `⚠️ Cần kiểm tra lại` thay vì tự động cho `✅ Đạt`.
    3. **Giảm chi phí xử lý False Positive cho người dùng:** Luôn đặt **câu trích dẫn trong bài của học viên** nằm ngay cạnh **tiêu chí gốc của Rubric** kèm số dòng để nếu AI có cảnh báo dư, học viên chỉ cần liếc mắt 5 giây là xác nhận được ngay.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường                                          | Nội dung                        |
| ----------------------------------------------- | ------------------------------- |
| **Actor**                                       | Học viên tham gia khóa Coding/AI Lab chuẩn bị nộp báo cáo cá nhân (`report/individual/*.md`) và báo cáo nhóm (`report/team/group_report.md`) trước deadline. |
| **Quy trình**                                   | 1. Thu thập và đối chiếu yêu cầu nằm ở nhiều file (`README`, `CHECKPOINTS`, `RUBRIC`, `SUBMISSION`, `worksheet`) → 2. Kiểm tra cấu trúc file, ô bảng trống, chữ mẫu thừa và tài nguyên đính kèm → 3. Đọc dò chéo nội dung đã viết với từng tiêu chí chấm của Rubric → 4. Tự chỉnh sửa các mục thiếu/chưa đạt và phát hiện điểm chưa thống nhất giữa các file hướng dẫn → 5. Commit & nộp bài. |
| **Bottleneck**                                  | **Bước 2 & Bước 3 (mất ~10–15 phút/lần nộp, trên tổng 15–20 phút rà soát):** Học viên phải mở nhiều file Markdown để cuộn đọc và đối chiếu bằng mắt thường lúc sát hạn nộp. Mắt người dễ bỏ lọt các lỗi định dạng/dòng mẫu thừa, hiểu thiếu yêu cầu chi tiết trong Rubric (như thiếu baseline/target), hoặc bối rối khi thông tin giữa các file hướng dẫn (`README` vs `SUBMISSION`) chưa thống nhất. |
| **Impact**                                      | Tốn **15–20 phút/lần nộp** (ước tính từ CP2/CP4) cho việc dò thủ công mỏi mắt; vẫn xảy ra tình trạng bỏ sót nội dung bắt buộc chỉ phát hiện sau khi đã nộp (ghi nhận 4/12 bài phải commit bổ sung ở nguồn cá nhân, hoặc mất điểm đáng tiếc ở các mục nhỏ trong Rubric). |
| **Success Metric** (baseline → target, cách đo) | • **Thời gian rà soát và xác minh yêu cầu trước khi nộp:** Giảm từ **15–20 phút/lần (baseline ước tính)** → **Dưới 3 phút/lần (target)** (gồm ~20 giây chạy công cụ + ~2 phút đọc cảnh báo và sửa).<br>• **Tỷ lệ bài nộp còn sót mục bắt buộc / lỗi cấu trúc cơ học:** Giảm về **0% đối với lỗi cấu trúc (nhờ Rule)** và **giảm ≥80% lỗi thiếu thành phần ngữ nghĩa theo Rubric**.<br>• *(Lưu ý minh bạch từ CP3–CP4: Các con số baseline hiện dựa trên ước lượng cá nhân và phỏng vấn minh họa; cần đo bấm giờ thực tế trên 5–10 học viên ở bước kiểm chứng tiếp theo trước khi chốt baseline cứng).* |
| **Boundary**                                    | • **Hệ thống KHÔNG ĐƯỢC:** Tự động viết thêm, sửa đè nội dung vào file báo cáo của học viên; không tự ý chọn một quy định khi phát hiện hai file hướng dẫn mâu thuẫn nhau; không tự động commit/nộp bài; không cam kết hay chấm điểm số cuối cùng thay giảng viên.<br>• **Con người kiểm tra (HITL):** Hệ thống chỉ xuất **Báo cáo kiểm tra chỉ đọc (Read-only Pre-submit Report)**; học viên giữ 100% quyền xem xét cảnh báo, hỏi lại TA khi có mâu thuẫn tài liệu, tự viết nội dung bổ sung và bấm nộp. |
| **AI intervention point**                       | Can thiệp ở **Bước 3 (Đối chiếu ngữ nghĩa nội dung bài làm với Rubric & phát hiện điểm mâu thuẫn giữa các tài liệu hướng dẫn)**, nằm ngay sau **Bước 2 (Rule-based quét cấu trúc/cú pháp cứng)** và trước **Bước 4 (Con người tự sửa bài)**. |
| **Mức chọn**                                    | **Workflow** *(Kết hợp **Rule** ở Bước 2 + **AI Workflow** cố định ở Bước 3)* |
| **Rủi ro & người kiểm tra**                     | • **Rủi ro chính:** (1) AI bỏ sót lỗi ngữ nghĩa tinh vi (False Negative) hoặc báo nhầm gây phiền (False Positive); (2) Học viên ỷ lại vào công cụ, chỉ sửa chỗ báo đỏ mà không đọc lại toàn bài.<br>• **Người kiểm tra:** Chính học viên nộp bài (kiểm tra qua đoạn trích dẫn gốc đặt cạnh cảnh báo) và Trưởng nhóm (khi rà soát `group_report.md` trước khi push). |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
| ------ | --- | --- | ---------- |
| **Nguyên nhân trong Quy trình & Bottleneck** | Chỉ tập trung vào việc học viên mỏi mắt đọc sót yêu cầu trong Rubric lúc khuya. | Bổ sung thêm nguyên nhân **yêu cầu phân tán và đôi khi chưa thống nhất giữa các file (`README`, `CHECKPOINTS`, `RUBRIC`, `SUBMISSION`)**. | Cập nhật trực tiếp từ kết quả CP4 (Interview P2, P3): khó khăn không chỉ do học viên đọc ẩu mà còn do tài liệu nằm ở nhiều file và có chỗ quy định khác nhau (ví dụ: cách đặt tên repo). |
| **Success Metric** | Ghi cứng baseline `18 phút → dưới 3 phút` và `4/12 bài → 0 bài` như số liệu đã đo chuẩn. | Tách rõ mục tiêu cho tầng Rule (0% lỗi cấu trúc) và tầng AI Workflow, đồng thời **ghi chú rõ baseline hiện tại là số ước tính cá nhân cần đo thực nghiệm thêm**. | Tuân thủ tính trung thực dữ liệu đã nêu ở CP3 & CP4: không biến con số ước tính của 1 cá nhân hoặc phỏng vấn giả lập thành số liệu đo lường toàn cục khi chưa test thật. |
| **Boundary** | Chỉ nêu AI không tự viết bài và không tự bấm nộp. | Bổ sung thêm: **AI không tự ý chọn/quyết định quy tắc khi phát hiện 2 tài liệu hướng dẫn mâu thuẫn nhau** (phải gắn cờ báo học viên hỏi TA/Giảng viên) và **không chấm điểm số thay giảng viên**. | Rút ra từ bài học của P3 ở CP4 và nghiên cứu Google NotebookLM ở mục 3.3: khi nguồn tài liệu mâu thuẫn, chỉ giảng viên mới có thẩm quyền xác nhận. |
| **Mức chọn & Điểm can thiệp** | Chưa chốt chính thức trong bảng Statement v0. | Chốt rõ **Rule (Bước 2) + AI Workflow (Bước 3)** và định vị chính xác điểm can thiệp. | Sau khi phân tích ma trận 6.1 và so sánh 4 mức ở 6.2, tách bạch rõ phần việc của Script/Regex và phần việc của LLM để tối ưu chi phí và độ tin cậy. |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

|   # | Tiêu chí | Đạt khi | Không đạt khi |
| --: | -------- | ------- | ------------- |
|   1 | **Độ phủ & Chính xác cấu trúc (Structural Recall - Tầng Rule)** | Phát hiện đúng **100%** các mục tiêu đề bị thiếu, ô bảng đang để trống, dòng chữ hướng dẫn mẫu chưa xóa, sai quy tắc tên file hoặc link ảnh trong `report/assets/` bị lỗi trên tập bài mẫu thử nghiệm. | Bỏ lọt bất kỳ một ô trống, mục bắt buộc bị thiếu hoặc link ảnh hỏng nào (False Negative ở tầng cấu trúc = 0%). |
|   2 | **Khả năng phát hiện lỗi thiếu thành phần ngữ nghĩa (Semantic Recall - Tầng AI)** | Phát hiện được **≥ 85%** các lỗi ngữ nghĩa điển hình được cài thử (seeded errors) theo Rubric (ví dụ: viết Metric thiếu con số `baseline → target`, viết Job Story chứa sẵn giải pháp AI, thiếu câu hỏi phản biện). | Cho qua (`✅ Đạt`) các mục viết chung chung, sáo rỗng hoặc thiếu hẳn vế bắt buộc đã ghi rõ trong `RUBRIC.md` / `CHECKPOINTS.md`. |
|   3 | **Có trích dẫn bằng chứng hai chiều (Groundedness & Traceability)** | **100%** các cảnh báo `❌/⚠️` mà AI đưa ra đều đính kèm chính xác: *(a) Số dòng / tên mục + câu trích dẫn nguyên văn trong bài học viên* và *(b) Câu yêu cầu tương ứng trích từ file `RUBRIC.md` / `CHECKPOINTS.md` / `SUBMISSION.md`*. | AI phán xét chung chung kiểu *"Mục này viết chưa tốt"* mà không chỉ ra được dòng nào trong bài đang vi phạm điều khoản nào của tài liệu gốc, hoặc tự bịa ra quy định không có trong repo. |
|   4 | **Tỷ lệ báo nhầm chấp nhận được (False Positive Rate)** | Tỷ lệ cảnh báo sai khiến học viên phải bấm "Bỏ qua (Ignore)" **≤ 20%** tổng số cảnh báo, và học viên chỉ mất **< 10 giây/cảnh báo** để xác minh nhờ có trích dẫn đặt cạnh nhau. | Báo lỗi tràn lan ở những mục học viên đã viết đầy đủ (> 20% báo nhầm), gây nhiễu và làm học viên mất nhiều thời gian hơn cả tự dò bằng mắt. |
|   5 | **Thời gian phản hồi & Tuân thủ Boundary (Latency & Safety)** | Tổng thời gian chạy toàn bộ pipeline (Rule + AI Workflow) cho 1 file báo cáo **≤ 25 giây**; đầu ra giữ nguyên định dạng **Read-only Report**, tuyệt đối không chỉnh sửa bất kỳ ký tự nào trong file bài làm gốc. | Thời gian chạy quá 1 phút (gây sốt ruột lúc sát deadline) hoặc tự ý ghi đè/sửa nội dung vào file `.md` của học viên. |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro          | Câu hỏi                                                           | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
| --------------- | ----------------------------------------------------------------- | ----------------------------------------------------- | ------------------ |
| **Value**       | Người dùng có thật sự cần và sẽ dùng không?                       | **Trung bình** | **Cơ sở tích cực:** Nỗi đau bỏ sót yêu cầu và mất 15–20 phút đọc chéo nhiều file đã được ghi nhận từ CP1/CP2 của 2 thành viên trong nhóm (#7 Nguyên, #11 Huy).<br>**Vì sao còn rủi ro TB:** Dữ liệu phỏng vấn ở CP4 hiện mới là *dữ liệu giả lập để minh họa*, và bản thân kết quả phân tích CP4 (P2) cũng chỉ ra rằng **một Checklist thủ công (No AI)** hoặc **Rule đơn giản** có thể đã giải quyết được phần lớn vấn đề mà chưa chắc học viên đã cần đến AI. |
| **Usability**   | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | **Thấp – Trung bình** | Thiết kế đầu ra dạng bảng đối chiếu **Read-only** đặt câu trích dẫn bài làm cạnh tiêu chí Rubric kèm cờ `✅/❌/⚠️` rất trực quan với học viên công nghệ. Rủi ro còn lại là nếu học viên chạy kiểm tra quá sát giờ đóng nộp (23h58) thì dù máy tìm ra lỗi trong 20 giây, học viên cũng không còn đủ thời gian để viết bổ sung tử tế. |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không?                     | **Thấp (An toàn)** | Toàn bộ dữ liệu đầu vào (`README.md`, `CHECKPOINTS.md`, `RUBRIC.md`, `SUBMISSION.md` và file báo cáo `.md`) đều là văn bản Markdown có cấu trúc rõ ràng, nằm sẵn trong repo và không chứa dữ liệu mật nhạy cảm. Việc viết script Python/Regex (Bước 2) kết hợp gọi LLM API theo Prompt cố định (Bước 3) hoàn toàn nằm trong khả năng kỹ thuật của các thành viên lớp AI. |
| **Viability**   | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành?     | **Thấp – Trung bình** | • **Quy định tổ chức (`RULES.md`):** Nhờ thiết kế **Boundary nghiêm ngặt (Read-only, không viết hộ, không chấm điểm thay)** nên giải pháp hoàn toàn tuân thủ quy chế học thuật của khóa đào tạo.<br>• **Chi phí & Vận hành:** Mỗi bài lab chỉ cần chạy kiểm tra 1–3 lần trước khi nộp (tốn ~vài nghìn token/lần, chi phí rất thấp). Tuy nhiên cần làm rõ ai là người cập nhật quy tắc nếu mỗi buổi lab có cấu trúc file khác nhau. |

### 8.2. Kết luận

**Quyết định:** **Not Yet** *(Chưa triển khai ngay phần AI Workflow; cần hoàn tất kiểm chứng thực tế thay cho dữ liệu giả lập CP4 và đo hiệu quả của đối chứng **No AI Checklist + Rule Script** trước khi quyết định nối thêm bước AI).*

**Lý do:**
1. **Trung thực với mức độ bằng chứng hiện tại:** Dù bài toán #7 rất sát thực tế học tập và khả thi về kỹ thuật (Feasibility thấp), nhưng ở CP3 các con số baseline (`15–20 phút`, `4/12 bài sót`) mới dựa trên ước tính cá nhân, và ở CP4 các cuộc phỏng vấn hiện đang là **dữ liệu giả lập để minh họa**. Theo nguyên tắc Discovery & Problem Framing, không thể bấm nút **Go** xây dựng hệ thống AI dựa trên dữ liệu kiểm chứng giả lập.
2. **Cần kiểm chứng giả thuyết "Checklist + Rule đã đủ chưa":** Ngay trong phân tích CP4 (trường hợp P2) và bảng 3.3, nhóm đã nhận thấy một **Master Checklist hợp nhất (No AI)** kết hợp với **Script kiểm tra ô trống/cấu trúc (Rule)** có thể đã ngăn chặn được phần lớn lỗi bỏ sót mục với chi phí bằng 0. Nhóm cần chứng minh bằng số liệu thật rằng học viên vẫn bị mất điểm ở phần *hiểu sai ngữ nghĩa Rubric* ngay cả khi đã có Checklist + Rule thì việc đưa **AI Workflow** vào mới thực sự tạo ra giá trị gia tăng (Value).

**Nếu Go — pilot nhỏ nhất:**
*(Khi đã đủ điều kiện chuyển sang Go)*: Không xây web app hay hệ thống phức tạp, mà làm **Pilot nhỏ nhất trong 1 buổi Lab tiếp theo** cho chính 4 thành viên **Nhóm 3 miền**:
1. Viết 1 script Python nhỏ (~50 dòng code) chạy trên VS Code local thực hiện **Bước 2 (Rule)**: quét file `report/individual/*.md` và `group_report.md` để báo các ô bảng trống, mục thiếu, dòng chữ mẫu chưa xóa và link ảnh lỗi.
2. Dùng 1 **Prompt chuẩn hóa (Workflow thủ công / Wizard-of-Oz)** nạp `RUBRIC.md` + `CHECKPOINTS.md` + file báo cáo vào công cụ sẵn có (như Google NotebookLM hoặc Claude/ChatGPT) để xuất bảng kiểm tra ngữ nghĩa `✅/❌/⚠️` trước khi `git push`.

**Nếu Not Yet — cần kiểm chứng gì trước:**
Trước khi viết code cho phần AI Workflow, nhóm cần thực hiện 2 bước kiểm chứng thật (mất khoảng 30–45 phút ngoài giờ):
1. **Kiểm chứng dữ liệu thật thay cho phỏng vấn giả lập:** Khảo sát nhanh 5–8 học viên thật trong lớp K5-L3A vừa nộp bài Lab Day 01 / Day 02 xem: *(a) Thực tế các bạn mất bao nhiêu phút để dò bài trước khi nộp? (b) Có bao nhiêu bạn thực sự bị quên mục / sai tên file / thiếu thành phần trong Rubric sau khi push?*
2. **Thử nghiệm A/B nhỏ với giải pháp No AI + Rule:** Cung cấp cho nhóm một bản **Master Checklist 1 trang** + **Script Rule quét ô trống** ở đầu buổi lab tới. Nếu chỉ cần Checklist + Rule đã giúp giảm tỷ lệ sót bài về 0 và thời gian kiểm tra xuống dưới 5 phút, nhóm sẽ dừng lại ở mức **Rule** mà không cần tốn công làm AI Workflow. Chỉ khi học viên vẫn mắc các lỗi ngữ nghĩa tinh vi (như viết Metric thiếu số đo, viết lạc yêu cầu Rubric), nhóm mới bật sang **Go** cho bước AI Workflow.

**Nếu No-Go — nên làm gì thay AI:**
Nếu sau khi kiểm chứng thực tế thấy học viên không cần AI hoặc chi phí duy trì prompt theo từng bài lab quá tốn công:
1. **Sửa quy trình tài liệu (No AI):** Đề xuất Ban đào tạo / TA bổ sung một mục **"Pre-submission Master Checklist"** thống nhất ngay ở cuối file template `MSSV_HoTen.md` và `group_report.md`, đồng thời đồng bộ hóa quy tắc đặt tên repo giữa `README.md` và `SUBMISSION.md`.
2. **Áp dụng Rule thuần túy (GitHub Actions / Linter):** Cài đặt sẵn một GitHub Action hoặc script kiểm tra cú pháp Markdown tự động báo đỏ khi phát hiện còn ô trống hoặc sai tên file mỗi khi học viên `git push`.

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):
- **Ngưỡng dừng 1 (Về nhu cầu & hiệu quả của Rule):** Nếu sau khi khảo sát thật **8 học viên** trong lớp và thử áp dụng **Master Checklist + Script Rule kiểm tra ô trống** trong **1 buổi Lab**, tỷ lệ bỏ sót yêu cầu bắt buộc đã giảm xuống **0 lỗi** và thời gian rà soát trung bình **≤ 4 phút/lần**, thì **dừng việc phát triển AI Workflow** và giữ giải pháp ở mức **No AI + Rule**.
- **Ngưỡng dừng 2 (Khi chạy thử Pilot AI Workflow):** Nếu trong đợt thử nghiệm Pilot trên **10 bản báo cáo**, tầng **AI Workflow** có tỷ lệ **báo lỗi nhầm (False Positive) > 25%**, hoặc **bỏ lọt (False Negative) > 15%** các lỗi ngữ nghĩa đã cài thử, hoặc tổng thời gian học viên phải đọc và xác minh cảnh báo của AI **lâu hơn 5 phút/lần** (không nhanh hơn tự đọc bằng mắt đáng kể), thì **ngừng dùng bước LLM tự động** và quay về phương án **Rule-based Linter + Checklist đối chiếu thủ công**.

---

## 9. Hạn chế và hướng tiếp theo

- **Hạn chế hiện tại của báo cáo nhóm:**
  1. **Về bằng chứng kiểm chứng (CP3 & CP4):** Số liệu baseline ban đầu (`15–20 phút`, `4/12 bài sót`) mới dựa trên ước lượng cá nhân của thành viên, chưa có log đo bấm giờ thực tế. Phần phỏng vấn ở Mục 3.2 hiện đang sử dụng **dữ liệu giả lập để minh họa** cấu trúc phân tích nên chưa thể dùng làm bằng chứng thực nghiệm để ra quyết định **Go** ngay lập tức.
  2. **Về sự đồng thuận trực tiếp:** Phần tổng hợp candidate ở CP3 và ghép nối quy trình CP5→CP6 có sự hỗ trợ cấu trúc từ AI; nhóm cần rà soát lại các câu hỏi phản biện trực tiếp giữa 4 thành viên (Hậu, Thịnh, Nguyên, Huy) để đảm bảo mọi con số được xác nhận đồng thuận.
- **Hướng tiếp theo ngay sau buổi Lab:**
  1. Thực hiện phỏng vấn ngắn 5 học viên thật trong lớp K5-L3A theo đúng câu hỏi Mom Test ở Mục 3.2 để thay thế toàn bộ dữ liệu giả lập bằng số liệu thực tế.
  2. Viết thử script Python kiểm tra cấu trúc file Markdown (Bước 2 - Rule) chạy thử ngay trên chính repo `K5-L3A-Day02-Nhom3mien-DiscoveryProblemFraming` để đo xem riêng tầng Rule đã bắt được bao nhiêu lỗi định dạng/bỏ trống mục.
  3. Kiểm nghiệm Prompt đối chiếu Rubric trên 4 báo cáo cá nhân của nhóm để đo tỷ lệ False Positive / False Negative thực tế so với 5 tiêu chí đánh giá đã đề ra ở Mục 7.

## 10. Tài liệu tham khảo

- Tài liệu hướng dẫn và bài mẫu của khóa học: [docs/01-worksheet.md](../../docs/01-worksheet.md), [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).
- Hệ thống quy định và tiêu chí đánh giá Lab Day 02: [README.md](../../README.md), [RULES.md](../../RULES.md), [CHECKPOINTS.md](../../CHECKPOINTS.md), [RUBRIC.md](../../RUBRIC.md), [SUBMISSION.md](../../SUBMISSION.md).
- Báo cáo cá nhân CP1–CP2 của 4 thành viên Nhóm 3 miền:
  - [Phan Trọng Hậu](../individual/2A202603547_PhanTrongHau.md)
  - [Ngô Đức Thịnh](../individual/2A202603548_NgoDucThinh.md)
  - [Đinh Trần Nguyên](../individual/03517_DinhTranNguyen.md)
  - [Bùi Gia Huy](../individual/2A202603525_BuiGiaHuy.md)
- Tài liệu công cụ đối chứng ở CP4:
  - GitHub Docs — [About Task Lists](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/about-tasklists)
  - GitHub Docs — [Understanding GitHub Actions Workflows](https://docs.github.com/en/actions/concepts/workflows-and-actions/workflows)
  - Google Support — [Google NotebookLM Help Center](https://support.google.com/gemininotebook/answer/16215270)
- Framework tham chiếu: *People + AI Guidebook (Google PAIR)* & *AI Canvas (Prediction Machines — Agrawal, Gans, Goldfarb)*.