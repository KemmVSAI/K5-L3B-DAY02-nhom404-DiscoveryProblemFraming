# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm. Khi chốt bản cuối, **mỗi thành viên copy file này vào repo cá nhân**.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: nhom404
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): 
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện (đặt ra khi pitch) |
|---:|---|---|---|---|---|
| 1 | Bùi Đức Tuấn | Khi kết thúc tuần học, tôi muốn tổng hợp lại kiến thức đã học để ôn tập nhanh và không bỏ sót nội dung quan trọng. | Sinh viên | Phải xem lại và tổng hợp bài học cũ, mất 1h30–2h/tuần. | Việc tổng hợp có thực sự giúp nhớ lâu hơn không, hay chỉ tạo bản tóm tắt mà ChatGPT đã làm được? |
| 2 | Bùi Đức Tuấn | Khi theo dõi chi tiêu ăn uống, tôi muốn biết tổng tiền đã chi và mức vượt ngân sách để điều chỉnh thói quen. | Cá nhân/sinh viên | Chi tiêu không được cộng dồn, đối chiếu thường xuyên; vượt 2–3 triệu/tháng trong 7 tháng liên tiếp. | Người dùng có sẵn sàng ghi từng khoản chi không? Vì sao không dùng ứng dụng quản lý chi tiêu hoặc bảng tính? |
| 3 | Bùi Đức Tuấn | Khi gặp lỗi trong quá trình làm lab, tôi muốn xác định và xử lý lỗi nhanh để tiếp tục hoàn thành bài. | Sinh viên làm lab | Chờ Discord khoảng 25 phút/lỗi, 3–4 lỗi/lab. | ChatGPT đã hỗ trợ debug được, vậy sản phẩm mới có thể truy cập dữ liệu hoặc môi trường nào mà chatbot thông thường không có? |
| 4 | Đinh Quốc Việt | Khi thực hiện bài lab có nhiều tài liệu hướng dẫn, tôi muốn đối chiếu và xác định đúng các yêu cầu bắt buộc để tránh làm thiếu hoặc sai deliverable. | Sinh viên làm lab | Đối chiếu 13 file Markdown, ước tính 1h30–2h/bài. | Nếu đưa toàn bộ tài liệu vào ChatGPT để tổng hợp thì sản phẩm mới còn tạo thêm giá trị gì? |
| 5 | Đinh Quốc Việt | Khi vận hành Agent NPC có nhiều thành phần, tôi muốn kiểm tra trạng thái và phát hiện sai lệch để xác định sự cố nhanh hơn. | Developer/người vận hành Agent NPC | Phải đối chiếu `/diagnostics`, `/status`, PID, module và source; HTTP 200 chưa chứng minh luồng hoạt động đúng. | Tại sao không dùng health check, logging và monitoring thông thường? Lợi thế nằm ở khả năng phát hiện lỗi nào? |
| 6 | Đinh Quốc Việt | Khi cập nhật repository, tôi muốn kiểm tra branch, remote và thay đổi file chính xác trước khi commit/push để tránh thao tác nhầm. | Developer/sinh viên lập trình | Phải kiểm tra thủ công Git state, mất 8–12 phút/lần. | Tại sao không dùng GitHub Desktop, Git alias hoặc script tự động thay vì xây một sản phẩm AI? |
| 7 | Nguyễn Mạnh Cường | Khi có bài tập và deadline từ nhiều môn, tôi muốn tập trung các nhiệm vụ vào một nơi để không bỏ sót hạn nộp. | Sinh viên | Thông tin phân tán ở LMS, email, nhóm chat và thông báo; mất 10–15 phút/ngày. | Calendar và task manager đã giải quyết được chưa? Sản phẩm mới có tự lấy và cập nhật deadline không? |
| 8 | Nguyễn Mạnh Cường | Khi di chuyển vào giờ cao điểm, tôi muốn lựa chọn lộ trình phù hợp để giảm thời gian và tránh tình trạng giao thông bất lợi. | Sinh viên/người đi làm | Dữ liệu giao thông biến động, thời gian dự kiến trên bản đồ có thể không chính xác. | Google Maps đã có dữ liệu giao thông và đề xuất tuyến đường, vậy sản phẩm mới có lợi thế dữ liệu nào? |
| 9 | Nguyễn Mạnh Cường | Khi mua và lưu trữ thực phẩm, tôi muốn theo dõi số lượng và hạn sử dụng để hạn chế thực phẩm bị quên, mua trùng hoặc hết hạn. | Hộ gia đình/người quản lý mua sắm | Thông tin không tập trung, khó theo dõi thực phẩm đang có; mất 10–15 phút/ngày. | Người dùng có thực sự lãng phí thực phẩm đủ nhiều để cần ứng dụng riêng không? Ai sẽ nhập dữ liệu và có sẵn sàng trả tiền không? |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A — Quản lý thông tin và công việc cá nhân | #1 Tổng hợp bài học; #4 Tổng hợp yêu cầu lab; #7 Quản lý deadline | Thông tin phân tán ở nhiều nguồn, người dùng phải tự đọc, lọc, đối chiếu và chuyển thành công việc hoặc kiến thức có cấu trúc. |
| B — Theo dõi và kiểm soát nguồn lực | #2 Ngân sách ăn uống; #9 Quản lý thực phẩm; #8 Lựa chọn lộ trình | Người dùng cần theo dõi trạng thái thay đổi theo thời gian và đưa ra quyết định nhằm giảm lãng phí, chi phí hoặc thời gian. |
| C — Chẩn đoán và xử lý vấn đề kỹ thuật | #3 Kẹt lỗi lab; #5 Kiểm tra trạng thái Agent NPC; #6 Quản lý thay đổi GitHub | Người dùng phải kiểm tra nhiều thông tin hoặc thành phần, xác định nguyên nhân sai lệch và lựa chọn hành động tiếp theo. |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm tình trạng vượt ngân sách ăn uống hằng tháng từ 2–3 triệu đồng xuống 0, đồng thời giúp người dùng kiểm soát số dư ngân sách tuần trong vòng 30 giây.
├── Opportunity A: Người dùng không nắm được số tiền còn lại trong ngân sách ăn uống vì các khoản chi nhỏ phát sinh liên tục và khó ghi nhớ tổng chi tiêu.
├── Opportunity B: Người dùng thường bỏ qua việc cộng dồn và đối chiếu chi tiêu với ngân sách tuần 500.000–1.000.000 đồng, đặc biệt khi bận hoặc chi tiêu gấp.
└── Opportunity C:  Người dùng chỉ nhận ra ngân sách đã bị vượt vào cuối tháng, khi không còn nhiều khả năng điều chỉnh thói quen chi tiêu.
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-Tạo ứng dụng quản lý ngân sách ăn uống.
-Tự động cộng dồn các khoản chi tiêu.
-Gửi thông báo khi đã sử dụng 70% ngân sách.
-Tạo dashboard hiển thị số dư ngân sách tuần.
-Sử dụng AI để phân tích và đưa ra lời khuyên chi tiêu.
-Kết nối TPBank, MoMo hoặc tài khoản ngân hàng để đồng bộ giao dịch.

### 2.4. Chấm điểm shortlist (1–5)


| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| **#2 — Quản lý chi tiêu** | 5 | 5 | 5 | 5 | 5 | 5 | 4 | **34/35** |
| **#5 — Kiểm tra trạng thái Agent NPC** | 5 | 5 | 4 | 4 | 3 | 5 | 3 | **29/35** |
| **#7 — Quản lý deadline học tập** | 5 | 4 | 2 | 4 | 4 | 5 | 3 | **27/35** |

**Candidate được chọn:** #2 — Quản lý chi tiêu: Người tiêu dùng, đặc biệt là sinh viên và người trẻ tự quản lý tài chính cá nhân, thường phát sinh nhiều khoản chi nhỏ cho đồ ăn vặt và ăn ngoài. Do thiếu công cụ theo dõi và đối chiếu chi tiêu thường xuyên với ngân sách, họ khó nhận biết tốc độ tiêu tiền và có nguy cơ vượt ngân sách ăn uống hằng tháng.

**Vì sao chọn:** Có nhóm người dùng tiềm năng là sinh viên và người trẻ tự quản lý tài chính, nhu cầu kiểm soát chi tiêu thiết thực, pain có bằng chứng ban đầu và impact đo lường được. Bài toán cũng phù hợp triển khai MVP trong thời gian lab.

**Vì sao loại các candidate còn lại:** #5 — Agent NPC diagnostics có thị trường ngách, hướng đến nhóm nhà phát triển và vận hành hệ thống AI. #7 — Quản lý deadline học tập có nhiều giải pháp thay thế như Calendar và task manager, chưa chứng minh được lợi thế cạnh tranh rõ ràng.

**Xử lý bất đồng (nếu có):** Nhóm ưu tiên #2 vì vấn đề có đối tượng người dùng tương đối rộng, nhu cầu kiểm soát chi tiêu thiết thực và kết quả có thể đo lường.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

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
| **Boundary** (AI không được làm gì) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô: Độ mơ hồ trung bình–cao, độ phức tạp thấp–trung bình.

Vì sao: Bài toán có độ mơ hồ trung bình–cao do nội dung giao dịch đôi khi không rõ ràng, nhưng độ phức tạp thấp–trung bình vì quy trình xử lý tương đối cố định. Vì vậy, AI chỉ hỗ trợ phân loại giao dịch; Rule xử lý tính toán và người dùng đưa ra quyết định, không cần Agent.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** | Người dùng tự ghi khoản chi vào Google Sheets hoặc ứng dụng quản lý chi tiêu. | Giao dịch ít, người dùng duy trì được thói quen ghi chép. | Dễ quên hoặc bỏ ghi chép; PV2 đã bỏ ghi tay sau 4 ngày. | Không chọn làm phương án chính |
| **Rule** | Dùng từ khóa hoặc mẫu nội dung để phân loại giao dịch; tự cộng dồn và cảnh báo theo ngưỡng. | Nội dung giao dịch rõ ràng, quy tắc phân loại ổn định. | Khó xử lý tên người bán lạ hoặc nội dung chuyển khoản không rõ. | Dùng cho bước tính toán và cảnh báo |
| **Workflow** | Nhận thông báo → AI phân loại và đánh giá độ tin cậy → người dùng xác nhận khi cần → Rule tính số dư và cảnh báo. | Quy trình cố định nhưng có một số giao dịch cần hiểu ngữ cảnh. | AI phân loại sai, người dùng phải xác nhận hoặc sửa nhãn. | **Chọn** |
| **Agent** | AI tự theo dõi chi tiêu, tự tìm dữ liệu, đề xuất hoặc thực hiện hành động kiểm soát ngân sách. | Khi cần xử lý nhiều tình huống chưa xác định trước và có đủ cơ chế kiểm soát. | Quá phức tạp, tăng quyền truy cập và rủi ro tài chính; không cần thiết với bài toán hiện tại. | Không chọn |

**Mức chọn:** Workflow có AI hỗ trợ phân loại giao dịch.

**Vì sao không chọn mức đơn giản hơn:** No AI phụ thuộc vào việc người dùng tự ghi chép, trong khi phỏng vấn cho thấy có người đã bỏ ghi tay sau 4 ngày. Rule có thể xử lý cộng dồn, tính số dư và cảnh báo nhưng khó phân loại các giao dịch có nội dung không rõ ràng. Vì vậy, nhóm chọn Workflow để AI hỗ trợ ở bước phân loại, còn Rule đảm nhiệm các phép tính và con người kiểm soát quyết định cuối cùng.

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction — AI dự đoán / tạo ra gì?** | Phân loại nội dung thông báo giao dịch thành ăn uống hoặc không phải ăn uống, kèm độ tin cậy của kết quả. |
| **Judgment — Con người cân nhắc, quyết định gì?** | Xác nhận hoặc sửa nhãn đối với giao dịch AI không chắc chắn; tự đánh giá số dư và quyết định có tiếp tục chi tiêu hay không. |
| **Action — Hành động cuối cùng là gì, ai làm?** | Rule tự cộng dồn chi tiêu, tính số dư và tạo cảnh báo. Người dùng quyết định mua tiếp, dừng chi hoặc điều chỉnh ngân sách. |
| **Outcome — Đo kết quả bằng gì?** | Số lần không kiểm tra ngân sách trước khi chi; số lần nạp thêm tiền; số tiền vượt ngân sách ăn uống mỗi tháng; tỷ lệ phân loại giao dịch chính xác. |
| **Input — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không?** | Nội dung thông báo giao dịch dạng văn bản, số tiền, thời gian và danh mục chi tiêu do người dùng xác nhận. Thông báo chỉ có sẵn nếu người dùng cấp quyền và hệ thống nhận được; giao dịch tiền mặt cần nhập thủ công. |
| **Feedback — Lấy phản hồi ở đâu để cải thiện?** | Nhãn người dùng xác nhận hoặc sửa, các giao dịch bị phân loại sai và dữ liệu chi tiêu được đối chiếu cuối tuần. |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng: Nhóm chọn Augment. AI chỉ hỗ trợ phân loại giao dịch và cảnh báo ngân sách; người dùng vẫn xác nhận giao dịch không rõ ràng và tự quyết định việc chi tiêu. Điều này phù hợp với CP4, khi người dùng vẫn muốn chủ động kiểm soát tiền của mình.
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào: Bỏ sót giao dịch ăn uống nguy hiểm hơn vì khiến số dư hiển thị cao hơn thực tế, dẫn đến nguy cơ chi vượt ngân sách. Nhóm xử lý bằng cách cho phép người dùng nhập thủ công, xác nhận giao dịch AI không chắc chắn và sửa nhãn để Rule tính lại số dư. Báo nhầm cũng được hạn chế bằng cơ chế xác nhận trước khi ghi nhận giao dịch có độ tin cậy thấp.

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
