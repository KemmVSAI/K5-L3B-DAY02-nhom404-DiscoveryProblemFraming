# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm:
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |
| 7 | | | | | |
| 8 | | | | | |
| 9 | | | | | |
| 10 | | | | | |
| 11 | | | | | |
| 12 | | | | | |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | | |
| B | | |
| C | | |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: 
├── Opportunity A: 
├── Opportunity B: 
└── Opportunity C: 
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |

**Candidate được chọn:**

**Vì sao chọn:**

**Vì sao loại các candidate còn lại:**

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

> Phần CP4 dưới đây được tổng hợp từ ghi chú nhóm cung cấp về vấn đề kiểm soát chi tiêu ăn vặt. Cần đối chiếu với candidate đã chọn ở mục 2 trước khi nộp; mục 2 hiện chưa được điền. Hai cuộc phỏng vấn là dữ liệu tự thuật do nhóm ghi nhận, chưa đủ để đại diện cho toàn bộ sinh viên/người đi làm. Ngày và hình thức phỏng vấn cụ thể chưa được ghi lại.

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Người gặp khó khăn với chi tiêu sẽ sẵn sàng trả tiền cho công cụ giúp kiểm soát chi tiêu. | Viability | 5 | 1 | Có — ghi chú hiện chưa xác nhận hành vi trả phí; một người nói rõ chưa từng trả phí cho ứng dụng quản lý tài chính. Cần hỏi thêm người đúng phân khúc và kiểm tra hành vi chi trả thực tế. |
| 2 | Cảnh báo khi đã dùng 70% ngân sách tuần có thể ngăn quyết định mua ăn vặt ngay tại quầy. | Value / Usability | 5 | 1 | Có — một người kể đã nạp thêm tiền tại quầy khi đi cùng đồng nghiệp; chưa thử cảnh báo 70%, nên đây là tín hiệu phản bác gián tiếp chứ chưa phải phép thử trực tiếp. |
| 3 | Ngân sách theo tháng phản hồi quá chậm để điều chỉnh hành vi chi tiêu trong tuần. | Value | 4 | 2 | Có — ghi nhận đây là nhận định sơ bộ; hai cuộc phỏng vấn chưa kiểm tra trực tiếp so sánh chu kỳ tuần/tháng. |
| 4 | Cách theo dõi thủ công có ma sát, còn tài khoản/hũ phụ có thể dễ dàng nạp thêm nên khó duy trì giới hạn. | Usability / Value | 4 | 2 | Có — một người kể đã bỏ ứng dụng ghi chép sau bốn ngày vì quên nhập một khoản; một người kể đã nạp thêm tiền từ tài khoản khác. Cần kiểm chứng với thêm người dùng và cách làm khác. |
| 5 | Khi hết ngân sách ăn vặt, người dùng không có lựa chọn thay thế phù hợp và có thể tiếp tục chi tiêu bằng tín dụng. | Value | 2 | 1 | Chưa — đây là giả định ít quan trọng hơn, chưa có bằng chứng trong hai cuộc phỏng vấn; không suy rộng từ ghi chú hiện có. |

Điểm quan trọng/bằng chứng là đánh giá sơ bộ của nhóm theo thang 1–5. Mức bằng chứng thấp phản ánh dữ liệu hiện có chủ yếu là hai lời kể, không phải kết quả định lượng hay kiểm chứng đại diện.

**Giả định nhóm ưu tiên kiểm chứng:** (1) mức sẵn sàng trả tiền và (2) cảnh báo có ảnh hưởng tới quyết định mua tại thời điểm phát sinh hay không. Hai cuộc phỏng vấn tạo tín hiệu phản bác ban đầu; chưa đủ để kết luận chắc chắn về toàn bộ phân khúc.

### 3.2. Kiểm chứng

**Cách đã dùng:** Hai phỏng vấn chớp nhoáng theo ghi chú nhóm cung cấp, tập trung vào hành vi chi tiêu và cách từng thử quản lý tiền. Ngày, kênh và thời lượng phỏng vấn chưa được ghi nhận. Không có survey/log định lượng.

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

#### Interview Snapshot #1

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Nhân viên văn phòng (ẩn danh; tên riêng và tuổi được lược bỏ). |
| Câu nói đáng nhớ nhất (nguyên văn theo ghi chú) | “Lúc đó đang đi cùng đồng nghiệp.” |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Theo lời kể, người được hỏi chuyển 1,5 triệu đồng vào MoMo đầu tháng để dành cho ăn vặt. Khi tiền hết vào tuần thứ ba, người này nạp thêm 500.000 đồng từ MBBank tại quầy khi đang đi cùng đồng nghiệp. Không có số liệu chi tiêu cả tuần vì người này không biết chính xác đã chi bao nhiêu. |
| Hiện đang xử lý bằng cách nào (workaround)? | Chuyển trước một khoản vào ví điện tử phụ; khi khoản đó hết thì có thể nạp thêm từ tài khoản ngân hàng. |
| Mất bao lâu, bao lần? | Một lần nạp thêm được nêu trong câu chuyện về tuần thứ ba; thời gian thao tác và tần suất chi tiêu chưa được ghi lại. |
| Insight / opportunity rút ra | Tài khoản tách riêng không nhất thiết tạo giới hạn khó vượt qua. Bối cảnh xã hội có thể ảnh hưởng đến quyết định chi tiêu; cần hỏi thêm về nhiều lần mua và kiểm tra trực tiếp tác động của cảnh báo, không khẳng định cảnh báo chắc chắn thất bại. |

#### Interview Snapshot #2

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Sinh viên năm cuối (ẩn danh; tên riêng và tuổi được lược bỏ). |
| Câu nói đáng nhớ nhất (nguyên văn theo ghi chú) | “Quên nhập 1 ly nước mía xong số dư bị lệch, nản quá bỏ luôn.” |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Theo lời kể, người được hỏi bị thiếu tiền tiêu vặt vào tháng trước. Trước đó đã tải ứng dụng Sổ Thu Chi (MISA), nhưng bỏ sau bốn ngày khi quên ghi một khoản mua nước mía và số dư theo dõi bị lệch. |
| Hiện đang xử lý bằng cách nào (workaround)? | Đã thử ghi chép bằng ứng dụng; hiện không có cách theo dõi ổn định nào được ghi nhận. |
| Mất bao lâu, bao lần? | Duy trì ứng dụng được bốn ngày; thời gian ghi mỗi giao dịch và tần suất thiếu tiền chưa được ghi lại. |
| Insight / opportunity rút ra | Bỏ sót một giao dịch nhỏ có thể làm người dùng mất tin tưởng vào số dư theo dõi. Đây là tín hiệu về ma sát ghi chép; một cuộc phỏng vấn chưa đủ để kết luận người dùng nói chung không chấp nhận trả phí. |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn chớp nhoáng theo ghi chú nhóm | 2 người (1 nhân viên văn phòng, 1 sinh viên năm cuối) | Có ví dụ về một người bỏ ghi chép sau bốn ngày và một người nạp thêm tiền khi khoản để riêng đã hết; cho thấy các cách tự theo dõi/tách tiền có thể có ma sát hoặc bị vượt qua trong những trường hợp này. | Một người nói rõ chưa từng trả phí cho ứng dụng quản lý tài chính; một trường hợp có yếu tố đi cùng đồng nghiệp khi mua. Chưa phỏng vấn đủ để kết luận về willingness-to-pay hoặc hiệu quả cảnh báo 70%. |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

Nhóm chuyển trọng tâm giả thuyết từ “cộng dồn và so ngân sách” sang khó khăn khi duy trì giới hạn chi tiêu tại thời điểm phát sinh: ghi chép có thể bị bỏ dở, khoản tách riêng có thể được nạp thêm, và bối cảnh xã hội có thể ảnh hưởng quyết định mua. Kết quả hiện tại **chưa chứng minh** hard-limit, khóa giao dịch theo MCC hay commitment contract là giải pháp phù hợp. Đây là các hướng cần kiểm chứng riêng; cần đánh giá tính khả thi, quyền kiểm soát của người dùng, rủi ro tài chính và phương án thoát/hoàn tiền trước khi đề xuất thử nghiệm. Không thu phí trực tiếp là giả thuyết kinh doanh mới, chưa được xác nhận bởi mẫu phỏng vấn này.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| YNAB — lập kế hoạch ngân sách | [YNAB](https://www.ynab.com/) | Hỗ trợ lập kế hoạch phân bổ tiền trước khi chi tiêu; có thể tham khảo cho bước đặt ngân sách theo nhóm mục tiêu. | Cách tiếp cận lập kế hoạch trước khi chi giúp người dùng chủ động phân bổ tiền. | Trang chính thức đã mở không đủ căn cứ cho nhận định cụ thể về màu cảnh báo, độ phức tạp khi đối soát hay khả năng đồng bộ với ngân hàng Việt Nam; cần kiểm tra tài liệu/tính năng cụ thể trước khi khẳng định. | Công cụ lập ngân sách không tự chứng minh rằng người dùng sẽ tuân thủ giới hạn tại quầy; nhóm cần kiểm tra hành vi và sự phù hợp với bối cảnh Việt Nam. |
| Money Lover — ghi chép và quản lý ngân sách | [Money Lover (trang tiếng Việt)](https://moneylover.me/vi) | Ghi nhận/phân loại thu chi, theo dõi ngân sách và xem báo cáo; trang giới thiệu nêu có nhập giao dịch thủ công và tự động. | Bao phủ bước ghi nhận và theo dõi chi tiêu; có thể dùng làm giải pháp sẵn có để so sánh thay vì tự xây lại. | Tài liệu trang giới thiệu không chứng minh ứng dụng chặn giao dịch tại quầy hay cảnh báo trước khi giao dịch. Nhận định về quét SMS và cảnh báo sau khi quẹt thẻ chưa được xác minh độc lập. | Phân biệt “biết ngân sách/chi tiêu” với “ngăn được giao dịch”; kiểm tra xem nhu cầu thật nằm ở theo dõi hay kiểm soát hành vi. |
| Timo — Hũ Chi Tiêu | [Timo](https://timo.vn/) | Chia tiền theo hũ và hỗ trợ quản lý tài chính cá nhân; có thể tham khảo cho bước phân bổ khoản chi. | Trang chính thức giới thiệu tính năng Hũ Chi Tiêu và công cụ quản lý tài chính trong ứng dụng. | Trang đã kiểm tra không đủ căn cứ cho khẳng định thẻ chỉ chi được từ một hũ, người dùng có thể nạp lại trong một thao tác, hoặc hũ tạo hard-limit. Cần xác minh điều kiện và luồng thao tác thực tế. | Không gọi cách chia hũ là “giới hạn cứng” nếu chưa kiểm tra quyền chuyển tiền và cơ chế thanh toán. |
| Beeminder — commitment contract (pattern tham khảo) | [Beeminder](https://www.beeminder.com/) | Theo dõi mục tiêu định lượng; trang chính thức mô tả có thể tính phí khi người dùng vượt đường mục tiêu. | Cho thấy một pattern cam kết có hậu quả tài chính khi không đạt mục tiêu đã đặt. | Chưa chứng minh pattern này phù hợp cho ngân sách ăn uống, có thể chấp nhận với người thu nhập hạn chế, hay tiền phạt được chuyển từ thiện. Cần kiểm tra điều khoản và thử nghiệm mức độ chấp nhận/rủi ro trước khi cân nhắc. | Commitment contract chỉ là giả thuyết để nghiên cứu thêm, không phải kết luận monetization. Cần bảo vệ quyền tự chủ, minh bạch cơ chế phạt và tránh làm trầm trọng thiếu hụt tài chính. |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
