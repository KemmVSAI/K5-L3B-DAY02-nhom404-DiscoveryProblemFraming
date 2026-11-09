# Báo cáo cá nhân — 2A202603885_DinhQuocViet

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).

## 1. Thông tin học viên
 
- Họ tên: Đinh Quốc Việt
- MSSV: 2A202603885
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: nhom404
- Link repository: https://github.com/KemmVSAI/K5-L3B-DAY02-nhom404-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi hoàn thành bài tập lập trình trên một repository được fork từ template, tôi muốn kiểm tra chính xác branch, remote, file đã thay đổi và trạng thái commit, để nộp đúng bài và không bỏ sót nội dung cần push. | Bản thân tôi, thành viên nhóm cùng thực hiện bài tập. | Đã xử lý ít nhất 2 repository học tập khác nhau, gồm K5 L3B Day01 và VinUni Codelab. Có các thao tác clone, fork, chỉnh sửa file, commit và push. Thời gian kiểm tra Git trước mỗi lần cập nhật ước tính khoảng **8–12 phút**, chưa được đo bằng đồng hồ. |
| 2 | Tốn thời gian | Khi chạy một project lập trình nhưng gặp lỗi môi trường hoặc lỗi API, tôi muốn xác định nguyên nhân và phạm vi ảnh hưởng, để tiếp tục thực hiện công việc mà không phải thử đi thử lại nhiều cách. | Bản thân tôi, người cùng phát triển hoặc sử dụng project. | Đã gặp ít nhất 3 dạng lỗi trong quá trình phát triển: kích hoạt Python virtual environment, lỗi HTTP 404 và lỗi HTTP 400 do giới hạn số lượng ảnh trong một prompt. Chưa ghi lại thời gian xử lý từng lỗi nên chưa có baseline thời gian đáng tin cậy. |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi nhận một bài lab có quy định và tiêu chí đánh giá nằm rải rác trong nhiều tài liệu, tôi muốn tổng hợp các yêu cầu, để không bỏ sót checkpoint hoặc nộp sai cấu trúc. | Bản thân tôi, các thành viên cùng làm bài. | Đã đọc và đối chiếu **13 file Markdown** để hiểu yêu cầu bài Discovery & Problem Framing. Tổng thời gian đọc, đối chiếu và tổng hợp ước tính khoảng **1 giờ 30 phút–2 giờ/bài lab**; chưa được đo bằng đồng hồ. |
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi lựa chọn mô hình ngôn ngữ để chạy trên máy tính có tài nguyên giới hạn, tôi muốn so sánh yêu cầu VRAM, context window và khả năng trả về dữ liệu có cấu trúc, để tránh chọn mô hình không phù hợp với hệ thống. | Bản thân tôi, người phát triển ứng dụng sử dụng mô hình. | Đã xem xét các cấu hình Qwen 3.5: bản 9B, 4B; bản 4B sử dụng khoảng 3,4 GB VRAM với context 8192; bản 2B gặp vấn đề với JSON mode. Đã có kết quả thực tế để so sánh nhưng chưa có bảng benchmark thống nhất. Dự án: https://github.com/VietAIMEM/autonomous-ai-npc |
| 5 | Lặp lại | Khi kiểm tra một hệ thống gồm backend và môi trường Unity, tôi muốn đối chiếu trạng thái các thành phần và kết quả thực thi, để xác định chính xác hệ thống đang hoạt động đến đâu và tránh kết luận sai khi chỉ một thành phần phản hồi thành công. | Bản thân tôi, người phát triển và kiểm thử. | Đã thực hiện nhiều đợt kiểm tra liên tiếp qua các phase 69B, 70A và 70B; theo dõi các endpoint `/diagnostics`, `/status`, PID và trạng thái module, trong đó có kết quả HTTP 200. Thời gian một lượt kiểm tra và đối chiếu ước tính khoảng **20–30 phút/lượt**, chưa được đo bằng đồng hồ. |
| 6 | Pain từ người khác | Chưa xác định được Job Story đủ rõ để đưa vào. | Chưa xác định. | Chưa có dữ liệu phỏng vấn, quan sát hoặc bằng chứng cụ thể từ người khác. Không tự đưa ra một vấn đề giả định khi chưa có dữ liệu xác nhận. |

**Nếu có dùng AI để gợi ý thêm:**

- Giữ lại: AI hỗ trợ rà soát cách diễn đạt Job Story, phân nhóm vấn đề theo các lăng kính và làm rõ quy trình, bottleneck, impact của từng vấn đề.
- Không đưa thêm: Những vấn đề chỉ được AI đề xuất nhưng chưa có trải nghiệm hoặc bằng chứng thực tế để xác nhận, đặc biệt là Pain từ người khác.
- Lý do: Muốn ưu tiên các vấn đề xuất phát từ trải nghiệm có thật, thay vì tạo thêm vấn đề chỉ để đủ số lượng.

**Lưu ý về số liệu:** Các khoảng thời gian 1 giờ 30 phút–2 giờ, 20–30 phút và 8–12 phút là ước tính sơ bộ dựa trên quy mô công việc đã thực hiện, chưa phải kết quả đo thời gian thực tế. Cần bấm giờ ở những lần thực hiện tiếp theo để xác định baseline chính xác.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Đọc, đối chiếu và tổng hợp yêu cầu từ nhiều tài liệu bài lab. | Đã có trải nghiệm đọc và đối chiếu 13 file Markdown cùng các tài liệu liên quan để xác định checkpoint, rubric, deliverable và quy định nộp bài. Có thể xác định rõ quy trình và kết quả đầu ra. Thời gian thực hiện ước tính khoảng **1 giờ 30 phút–2 giờ/bài lab**, mục tiêu đề xuất giảm xuống khoảng **45 phút**. | Chưa đo thời gian thực tế ở từng bước, thời gian đối chiếu và số lần phải quay lại tài liệu. Cần kiểm tra mức độ lặp lại ở các bài lab khác. |
| 2 | Kiểm tra và đối chiếu trạng thái hoạt động của các thành phần trong dự án Agent NPC (https://github.com/VietAIMEM/autonomous-ai-npc). | Đã thực hiện nhiều đợt kiểm tra tại các phase 69B, 70A và 70B; có dữ liệu từ `/diagnostics`, `/status`, PID và trạng thái các module. Quy trình có nhiều bước đối chiếu cụ thể. Thời gian một lượt kiểm tra ước tính khoảng **20–30 phút**, mục tiêu đề xuất giảm xuống **10–15 phút**. | Chưa đo thời gian thực tế của từng bước. Chưa xác định chính xác bước nào chiếm nhiều thời gian nhất trong toàn bộ quy trình. |
| 3 | Kiểm tra và quản lý thay đổi khi đưa bài tập từ repository local lên GitHub. | Đã thực hiện clone, fork, chỉnh sửa, commit và push trên nhiều repository học tập. Có nhu cầu kiểm tra remote, branch và các file thay đổi để tránh bỏ sót hoặc đưa nhầm nội dung lên repository. Thời gian kiểm tra ước tính khoảng **8–12 phút/lần cập nhật**, mục tiêu đề xuất giảm xuống **3–5 phút**. | Chưa đo thời gian thực tế và chưa thống kê tần suất phát hiện file thay đổi ngoài dự kiến. Cần kiểm tra thêm mức độ phức tạp khi repository có nhiều branch hoặc remote. |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi phải thực hiện một bài lab có yêu cầu nằm rải rác trong nhiều tài liệu, tôi muốn xác định và tổng hợp đầy đủ các checkpoint, deliverable, rubric và quy định nộp bài, để không bỏ sót yêu cầu hoặc thực hiện sai thứ tự. |
| Actor | Bản thân tôi. |
| Thời điểm / bối cảnh | Khi bắt đầu một bài lab có nhiều file hướng dẫn, template và tiêu chí đánh giá khác nhau. Ví dụ: bài Discovery & Problem Framing có 13 file Markdown cùng các tài liệu liên quan. |
| Quy trình hiện tại (3–7 bước) | 1. Mở README và xác định mục tiêu bài lab. 2. Đọc RULES, CHECKPOINTS, RUBRIC và SUBMISSION để tìm yêu cầu chính thức. 3. Đọc worksheet và bài mẫu để hiểu cách thực hiện từng checkpoint. 4. Mở template báo cáo cá nhân và kiểm tra các mục cần điền. 5. Đối chiếu thông tin giữa các tài liệu để phát hiện yêu cầu trùng lặp hoặc chưa thống nhất. 6. Tổng hợp thành danh sách công việc và checklist hoàn thành. |
| Bottleneck (bước nào, mất bao nhiêu phút) | **Bước 5 – Đối chiếu thông tin giữa nhiều tài liệu.** Phải quay lại các file khác nhau để xác định đâu là yêu cầu bắt buộc, đâu là ví dụ và đâu chỉ là đề xuất. Đã phát hiện điểm chưa thống nhất liên quan đến cách lưu sơ đồ Mermaid. Thời gian toàn bộ quy trình ước tính khoảng **1 giờ 30 phút–2 giờ/bài lab**; riêng bước đối chiếu ước tính khoảng **30–45 phút**. Đây là số liệu ước tính, chưa được bấm giờ thực tế. |
| Impact (nếu không giải thì sao) | Có thể hiểu sai yêu cầu, bỏ sót checkpoint, điền sai template hoặc nộp thiếu deliverable. Điều này dẫn đến phải làm lại, mất thêm thời gian và có nguy cơ bị trừ điểm theo rubric. |
| Success metric (baseline → target) | **Baseline ước tính:** 1 giờ 30 phút–2 giờ/bài lab cho việc đọc và tổng hợp 13 file Markdown. Chưa có số liệu về số yêu cầu bị bỏ sót. **Target đề xuất:** giảm thời gian chuẩn bị xuống khoảng 45 phút; 100% yêu cầu bắt buộc được ghi vào checklist và liên kết với tài liệu nguồn; không bỏ sót deliverable bắt buộc. Cách đo: bấm giờ từng bước, đối chiếu checklist với tài liệu gốc và ghi nhận số yêu cầu bị bỏ sót. |
| Phương án không dùng AI | Tạo bảng checklist theo từng checkpoint; lập mục lục liên kết đến tài liệu nguồn; sử dụng bảng tính để đánh dấu yêu cầu đã đọc, đã thực hiện và đã kiểm tra. |
| Giả thuyết về AI (nếu có) | AI có thể hỗ trợ trích xuất và phân loại yêu cầu từ nhiều tài liệu, phát hiện các điểm khác nhau giữa các file và tạo bản checklist ban đầu. Người học vẫn phải kiểm tra lại nội dung theo tài liệu gốc. |
| Cảm nhận nhanh | **Workflow** (giả thuyết): cần kiểm tra xem việc tổ chức lại tài liệu, quy trình đọc và checklist có đủ giải quyết bottleneck hay không trước khi phát triển thành công cụ AI. |

**Quy trình nháp hiện tại:**

Bắt đầu nhận bài lab → Đọc README → Đọc RULES, CHECKPOINTS, RUBRIC, SUBMISSION → Đọc worksheet và bài mẫu → Kiểm tra template báo cáo → Đối chiếu yêu cầu giữa các file (**BOTTLENECK**) → Tổng hợp checklist công việc → Hoàn thành việc chuẩn bị.

```text
Bắt đầu nhận bài lab
       |
       v
1. Đọc README
   Thời gian: Ước tính 5–10 phút
       |
       v
2. Đọc RULES, CHECKPOINTS,
   RUBRIC và SUBMISSION
   Thời gian: Ước tính 20–30 phút
       |
       v
3. Đọc worksheet và bài mẫu
   Thời gian: Ước tính 20–25 phút
       |
       v
4. Kiểm tra template báo cáo
   Thời gian: Ước tính 10–15 phút
       |
       v
5. Đối chiếu yêu cầu giữa các file
   BOTTLENECK
   Thời gian: Ước tính 30–45 phút
       |
       v
6. Tổng hợp checklist công việc
   Thời gian: Ước tính 5–10 phút
       |
       v
Hoàn thành việc chuẩn bị

Tổng thời gian: Ước tính 1 giờ 30 phút–2 giờ
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi cần kiểm tra trạng thái hoạt động của một hệ thống Agent NPC gồm nhiều thành phần backend và Unity, tôi muốn đối chiếu kết quả kiểm tra từ các endpoint, tiến trình và module, để xác định chính xác thành phần nào đang hoạt động và tránh kết luận sai về trạng thái toàn hệ thống. |
| Actor | Bản thân tôi. |
| Thời điểm / bối cảnh | Khi kiểm tra hệ thống sau một lần thay đổi mã nguồn, khởi động lại backend hoặc thực hiện một phase kiểm thử. |
| Quy trình hiện tại (3–7 bước) | 1. Xác định phase cần kiểm tra và trạng thái mong đợi của hệ thống. 2. Kiểm tra tiến trình backend và PID để xác định dịch vụ có đang chạy hay không. 3. Gửi yêu cầu đến các endpoint `/diagnostics` và `/status` để lấy thông tin trạng thái. 4. Kiểm tra trạng thái từng module và các thành phần liên quan. 5. Đối chiếu thông tin giữa endpoint, PID, trạng thái module, nguồn mã đang chạy và kết quả log. 6. Tổng hợp kết quả, xác định thành phần đã đạt, chưa đạt hoặc cần kiểm tra thêm. |
| Bottleneck (bước nào, mất bao nhiêu phút) | **Bước 5 – Đối chiếu trạng thái giữa nhiều nguồn thông tin.** Một endpoint trả về HTTP 200 chỉ xác nhận yêu cầu được xử lý thành công, chưa chứng minh tất cả module hoặc chức năng thực tế hoạt động đúng. Ví dụ Phase 70B có `/diagnostics` và `/status` trả về 200 nhưng kết quả source parity vẫn ở mức partial. Thời gian toàn bộ một lượt kiểm tra ước tính khoảng **20–30 phút**; riêng bước đối chiếu ước tính khoảng **10–15 phút**. Đây là số liệu ước tính, chưa được bấm giờ thực tế. |
| Impact (nếu không giải thì sao) | Có nguy cơ kết luận hệ thống hoạt động bình thường trong khi một số module chưa được kích hoạt hoặc chưa đồng nhất với mã nguồn mong đợi. Việc này có thể dẫn đến kiểm thử sai, lặp lại các bước chẩn đoán hoặc đưa ra quyết định xử lý không phù hợp. |
| Success metric (baseline → target) | **Baseline ước tính:** 20–30 phút/lượt kiểm tra. Chưa đo thời gian thực tế và chưa thống kê tỷ lệ kết luận trạng thái chính xác. **Target đề xuất:** giảm thời gian kiểm tra xuống khoảng 10–15 phút/lượt; 100% lượt kiểm tra ghi nhận đầy đủ HTTP status, PID, trạng thái module và kết quả đối chiếu nguồn; không kết luận toàn hệ thống đạt chỉ dựa trên HTTP 200. Cách đo: bấm giờ từng bước và đối chiếu checklist với trạng thái thực tế của từng thành phần. |
| Phương án không dùng AI | Sử dụng checklist kiểm thử cố định; viết script kiểm tra endpoint, PID và trạng thái module; tổng hợp kết quả thành bảng trạng thái PASS, FAIL hoặc PARTIAL để người phát triển xem xét. |
| Giả thuyết về AI (nếu có) | AI có thể hỗ trợ tổng hợp log và kết quả kiểm tra từ nhiều nguồn, chỉ ra các trạng thái không nhất quán và giải thích nguyên nhân có thể xảy ra. Người phát triển vẫn phải xác minh bằng dữ liệu runtime trước khi kết luận. |
| Cảm nhận nhanh | **Rule** (giả thuyết): nên kiểm tra xem checklist và script kiểm tra cố định có giải quyết được phần lớn bottleneck hay không trước khi cần đến AI. |

**Quy trình nháp hiện tại:**

```text
Bắt đầu kiểm tra hệ thống
       |
       v
1. Xác định phase và trạng thái
   mong đợi
   Thời gian: Ước tính 2–3 phút
       |
       v
2. Kiểm tra tiến trình backend và PID
   Thời gian: Ước tính 3–5 phút
       |
       v
3. Kiểm tra /diagnostics và /status
   Thời gian: Ước tính 2–3 phút
       |
       v
4. Kiểm tra trạng thái các module
   Thời gian: Ước tính 3–4 phút
       |
       v
5. Đối chiếu endpoint, PID, module,
   source và log
   BOTTLENECK
   Thời gian: Ước tính 10–15 phút
       |
       v
6. Tổng hợp kết quả kiểm tra
   Thời gian: Ước tính 2–3 phút
       |
       v
Hoàn thành đánh giá trạng thái

Tổng thời gian: Ước tính 20–30 phút
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi hoàn thành bài tập trên một repository local được clone từ GitHub hoặc từ repository đã fork, tôi muốn kiểm tra các thay đổi, branch và remote trước khi commit và push, để đảm bảo nội dung được đưa lên đúng repository và không bỏ sót hoặc đưa nhầm file ngoài dự kiến. |
| Actor | Bản thân tôi. |
| Thời điểm / bối cảnh | Khi hoàn thành việc chỉnh sửa source code, notebook, báo cáo hoặc các file tài liệu trong repository của bài tập và chuẩn bị nộp bài trên GitHub. |
| Quy trình hiện tại (3–7 bước) | 1. Kiểm tra thư mục repository local đang làm việc. 2. Kiểm tra branch hiện tại bằng Git. 3. Kiểm tra remote để xác định repository đích. 4. Kiểm tra trạng thái file thay đổi bằng `git status` và nội dung bằng `git diff`. 5. Chọn các file cần đưa vào commit, tạo commit với thông điệp phù hợp. 6. Push commit lên đúng branch và kiểm tra kết quả trên GitHub. |
| Bottleneck (bước nào, mất bao nhiêu phút) | **Bước 3–4 – Xác minh remote, branch và kiểm tra các file thay đổi trước khi commit.** Cần phân biệt file được chỉnh sửa có chủ đích với file thay đổi ngoài dự kiến. Đã từng phải kiểm tra lý do README xuất hiện trong các thay đổi khi thực hiện nộp bài GitHub. Thời gian toàn bộ một lần cập nhật ước tính khoảng **8–12 phút**; riêng bước kiểm tra remote, branch và file thay đổi ước tính khoảng **3–5 phút**. Đây là số liệu ước tính, chưa được bấm giờ thực tế. |
| Impact (nếu không giải thì sao) | Có thể push nhầm repository hoặc branch, bỏ sót file cần nộp, đưa file không mong muốn lên GitHub hoặc tạo commit chứa những thay đổi chưa được kiểm tra. Điều này có thể khiến phải sửa commit, push lại hoặc ảnh hưởng đến kết quả nộp bài. |
| Success metric (baseline → target) | **Baseline ước tính:** 8–12 phút/lần cập nhật. Chưa đo thời gian thực tế và chưa thống kê số lần phát hiện thay đổi ngoài dự kiến. **Target đề xuất:** giảm thời gian kiểm tra xuống khoảng 3–5 phút/lần; 100% lần push đều được kiểm tra remote, branch và danh sách file thay đổi trước khi commit; không push nhầm repository hoặc branch. Cách đo: bấm giờ quy trình và kiểm tra checklist trước push, sau đó đối chiếu với repository GitHub đích. |
| Phương án không dùng AI | Sử dụng checklist trước khi push; kiểm tra bằng `git status`, `git remote -v`, `git branch --show-current`, `git diff` và `git log`; chỉ staging những file đã xác nhận. |
| Giả thuyết về AI (nếu có) | AI có thể hỗ trợ giải thích Git status, phân tích nội dung diff và cảnh báo những thay đổi có khả năng ngoài dự kiến. Tuy nhiên, người dùng vẫn phải xác nhận repository, branch và quyết định commit/push. |
| Cảm nhận nhanh | **Rule** (quy trình kiểm tra Git có thể chuẩn hóa bằng checklist và các lệnh kiểm tra cố định, chưa cần Agent). |

**Quy trình nháp hiện tại:**

```text
Bắt đầu hoàn thành bài tập
       |
       v
1. Xác định thư mục repository local
   Thời gian: Ước tính 1 phút
       |
       v
2. Kiểm tra branch hiện tại
   Thời gian: Ước tính 1 phút
       |
       v
3. Kiểm tra remote repository
   Thời gian: Ước tính 1–2 phút
       |
       v
4. Kiểm tra file thay đổi bằng
   git status và git diff
   BOTTLENECK
   Thời gian: Ước tính 2–3 phút
       |
       v
5. Chọn file, staging và commit
   Thời gian: Ước tính 2–3 phút
       |
       v
6. Push và kiểm tra trên GitHub
   Thời gian: Ước tính 1–2 phút
       |
       v
Hoàn thành việc cập nhật repository

Tổng thời gian: Ước tính 8–12 phút
```

### Card muốn pitch nhất

- **Card số:** 1
- **Vì sao:** Đây là vấn đề có trải nghiệm gần nhất và bằng chứng cụ thể từ bài lab Discovery & Problem Framing. Tôi đã phải đọc và đối chiếu 13 file Markdown cùng các tài liệu liên quan để phân biệt yêu cầu bắt buộc, ví dụ và đề xuất. Thời gian thực hiện ước tính khoảng 1 giờ 30 phút–2 giờ. Quy trình có thể mô tả thành các bước rõ ràng, có điểm nghẽn ở bước đối chiếu thông tin và có thể đánh giá bằng thời gian hoàn thành, tỷ lệ yêu cầu được ghi nhận đầy đủ trong checklist. Ngoài ra, đây cũng là tình huống có khả năng xuất hiện ở nhiều học viên khi thực hiện các bài lab có nhiều tài liệu hướng dẫn.
- **Câu hỏi muốn nhóm phản biện:** Khi thực hiện một bài lab có nhiều file hướng dẫn, các bạn thường mất thời gian nhất ở bước nào? Đã từng có lần nào hiểu sai yêu cầu, bỏ sót checkpoint hoặc phải quay lại nhiều tài liệu để xác nhận thông tin chưa? Hãy kể lại lần gần nhất và cách các bạn xử lý.

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Card #1 mô tả bước đối chiếu tài liệu là bottleneck nhưng chưa chỉ rõ loại thông tin cần đối chiếu và tình huống gây khó khăn. | Đồng ý. | Làm rõ bước 5 là đối chiếu yêu cầu bắt buộc, ví dụ và đề xuất giữa nhiều file. Bổ sung ví dụ về điểm chưa thống nhất trong hướng dẫn lưu sơ đồ Mermaid. |
| Card #1 chưa chứng minh vấn đề này đủ phổ biến để phát triển thành một sản phẩm thương mại. | Đồng ý một phần. | Đây là nhận định hợp lý vì bằng chứng hiện tại chủ yếu đến từ trải nghiệm cá nhân. Tuy nhiên, tôi chưa loại bỏ vấn đề này mà sẽ kiểm chứng thêm với học viên ở các lớp hoặc chương trình đào tạo khác để xác định mức độ phổ biến và nhu cầu thực tế. |
| Card #2 có thể nhầm lẫn giữa việc endpoint trả HTTP 200 và việc toàn bộ hệ thống hoạt động đúng. | Đồng ý. | Bổ sung bước đối chiếu endpoint, PID, trạng thái module, source và log. Metric không chỉ kiểm tra HTTP status mà còn phải ghi nhận trạng thái từng thành phần. |
| Card #3 có thể tự động hóa toàn bộ quy trình commit và push để tiết kiệm thời gian. | Không đồng ý. | Tôi không muốn tự động hóa hoàn toàn thao tác push vì có rủi ro đưa nhầm file, nhầm branch hoặc nhầm repository. Nên ưu tiên công cụ kiểm tra và cảnh báo trước khi người dùng xác nhận các thao tác thay đổi repository. |
| Card #3 chưa làm rõ rủi ro khi có nhiều remote hoặc nhiều branch trong cùng một repository. | Đồng ý. | Bổ sung bước kiểm tra remote và branch trước khi staging, commit và push. Làm rõ hậu quả của việc đưa nhầm file hoặc push sai repository. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Trình bày ba candidate: #4 — Tổng hợp yêu cầu lab; #5 — Kiểm tra trạng thái Agent NPC; #6 — Kiểm tra thay đổi GitHub. Làm rõ Job Story, Actor, bottleneck và câu hỏi cần phản biện của từng vấn đề. | Bổ sung ba vấn đề xuất phát từ trải nghiệm phát triển và vận hành phần mềm. Trong đó, candidate #5 được đưa vào shortlist để nhóm tiếp tục xem xét. |
| Phản biện bài của bạn khác | Đã chuẩn bị các câu hỏi phản biện cho các candidate, tập trung vào giá trị thực tế, mức độ khác biệt so với công cụ có sẵn và khả năng triển khai. Chưa có ghi chép xác nhận đầy đủ câu hỏi thực tế đã đặt cho từng thành viên. | Giúp xác định vấn đề cần làm rõ trước khi chọn candidate, tránh chỉ dựa trên việc một giải pháp có thể xây dựng được hay không. |
| Nhận phản biện | Các candidate được đặt câu hỏi về khả năng giải quyết bằng công cụ có sẵn, đặc biệt là việc sử dụng health check, logging và monitoring thông thường cho bài toán Agent NPC. | Làm rõ rằng HTTP 200 hoặc một endpoint phản hồi thành công chưa đủ chứng minh toàn bộ hệ thống hoạt động đúng. Cần xác định giá trị nằm ở việc đối chiếu trạng thái thực tế giữa nhiều thành phần. |
| Gom cluster / cây OST | Tham gia phân nhóm các candidate thành ba cluster: A — Quản lý thông tin và công việc cá nhân; B — Theo dõi và kiểm soát nguồn lực; C — Chẩn đoán và xử lý vấn đề kỹ thuật. Tham gia xây dựng OST cho candidate được nhóm lựa chọn. | Các vấn đề được gom theo pattern chung thay vì gom theo giải pháp. Nhóm sử dụng Outcome là giảm tình trạng vượt ngân sách ăn uống và xây dựng ba Opportunity liên quan đến khả năng nắm số dư, duy trì đối chiếu và phát hiện nguy cơ vượt ngân sách. |
| Chọn candidate problem | Tham gia xem xét các candidate theo actor, quy trình, bằng chứng pain, impact, tính khả thi và khả năng so sánh No AI / Rule / Workflow / Agent. | Nhóm chọn #2 — Quản lý chi tiêu ăn uống với 34/35 điểm. Candidate #5 — Kiểm tra trạng thái Agent NPC đạt 29/35 điểm nhưng không được chọn làm problem chính. |
| Kiểm chứng / research | Không trực tiếp phụ trách CP4 trong phạm vi phân công cá nhân. | Không tự nhận kết quả phỏng vấn, survey hoặc research của thành viên khác là phần việc cá nhân. |
| Quy trình nhóm | Không trực tiếp phụ trách CP5. | Các nội dung quy trình trước/sau và Problem Statement v0 được giữ theo phần tổng hợp chung của nhóm. |
| Problem Statement | Không trực tiếp phụ trách xây dựng Problem Statement v0 hoặc v1. | Sử dụng kết quả thống nhất của nhóm làm cơ sở cho phần giải thích tại mục 6.7. |
| Mức can thiệp AI | Phụ trách phần nhỏ CP6 là mục 6.4 — Hai câu hỏi của Google PAIR. | Làm rõ định hướng Augment thay vì Automate và xác định cách xử lý hai loại lỗi AI: báo nhầm và bỏ sót giao dịch. |
| Quyết định | Tham gia quá trình lựa chọn và thống nhất kết quả chung. Không trực tiếp phụ trách toàn bộ đánh giá rủi ro và quyết định Go / Not Yet / No-Go. | Nhóm chọn candidate #2 — Quản lý chi tiêu ăn uống và định hướng Workflow có AI hỗ trợ phân loại giao dịch. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Hỗ trợ rà soát cách diễn đạt Job Story và phân loại vấn đề theo các lăng kính. | Giúp trình bày trải nghiệm theo cấu trúc Khi… tôi muốn… để… và làm rõ Actor, dấu hiệu thực tế. | Có thể gợi ý thêm các vấn đề nghe hợp lý nhưng chưa có trải nghiệm hoặc bằng chứng xác nhận. | Chỉ giữ các vấn đề đã từng trực tiếp gặp. Không tự tạo Pain từ người khác khi chưa phỏng vấn hoặc quan sát. |
| CP2 Problem Card | Hỗ trợ cấu trúc Problem Card, xác định bottleneck, impact và success metric. | Giúp chia quy trình thành các bước cụ thể và chỉ ra vị trí có khả năng gây tốn thời gian. | Một số nhận xét có thể suy rộng quá mức từ trải nghiệm cá nhân, hoặc mặc định rằng vấn đề đã đủ phổ biến để xây dựng sản phẩm. | Phân biệt số liệu ước tính với baseline đo thực tế; ghi rõ những điều còn cần kiểm chứng. |
| CP4 Research | Không trực tiếp phụ trách checkpoint này. | Chưa ghi nhận đóng góp cá nhân cụ thể. | Không có đủ dữ liệu để đánh giá. | Không nhận phần research của thành viên khác là kết quả cá nhân. |
| CP5 Quy trình | Không trực tiếp phụ trách checkpoint này. | Chưa ghi nhận đóng góp cá nhân cụ thể. | Không có đủ dữ liệu để đánh giá. | Giữ đúng phạm vi công việc được phân công. |
| CP5–6 Problem Statement | Không trực tiếp phụ trách xây dựng Problem Statement. | Có thể hỗ trợ rà soát tính nhất quán giữa problem, quy trình và metric khi cần. | Không nên xem nội dung AI tạo ra là bằng chứng kiểm chứng vấn đề. | Sử dụng kết quả thống nhất của nhóm, không tự nhận là người thực hiện phần này. |
| CP6 Mức can thiệp / quyết định | Sử dụng AI hỗ trợ diễn đạt và phản biện hai câu hỏi Google PAIR tại mục 6.4. | Giúp phân biệt Augment và Automate, đồng thời phân tích hậu quả của báo nhầm và bỏ sót giao dịch. | Câu trả lời chung chung có thể chỉ khẳng định AI cần con người giám sát mà chưa giải thích rõ lý do. | Gắn câu trả lời với bài toán quản lý chi tiêu: người dùng vẫn kiểm soát tiền, giao dịch không rõ cần xác nhận và bỏ sót giao dịch ăn uống có thể làm sai lệch số dư. |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Khi nghe các vấn đề của các thành viên khác, tôi nhận ra mỗi người có những khó khăn khác nhau dù đều xuất phát từ nhu cầu giải quyết công việc hằng ngày. Candidate quản lý chi tiêu tập trung vào việc kiểm soát ngân sách, quản lý deadline liên quan đến việc tổng hợp thông tin từ nhiều nguồn, còn các vấn đề kỹ thuật của tôi tập trung vào kiểm tra và xử lý hệ thống. Tôi học được rằng không nên chỉ đánh giá một vấn đề dựa trên mức độ quen thuộc hoặc khả năng triển khai kỹ thuật. Cần xem xét Actor, mức độ ảnh hưởng, tần suất và bằng chứng thực tế. Ví dụ, candidate Agent NPC của tôi có quy trình khá rõ nhưng đối tượng sử dụng tương đối hẹp, trong khi quản lý chi tiêu có nhóm người dùng tiềm năng rộng hơn. Qua việc so sánh và chấm điểm, tôi hiểu rằng một vấn đề đáng chọn không nhất thiết phải phức tạp về kỹ thuật mà cần có nhu cầu thực tế, tác động đo được và phù hợp với thời gian thực hiện của nhóm.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
Có, khi thảo luận về quản lý chi tiêu, nhóm đã đưa ra những ý tưởng như tạo ứng dụng, dashboard, tự động cộng dồn giao dịch và gửi thông báo khi sử dụng 70% ngân sách. Tôi nhận ra những nội dung này đang mô tả giải pháp thay vì khó khăn thực tế của người dùng. Nhóm đã quay lại xác định Outcome và các Opportunity trong Opportunity Solution Tree. Thay vì xem dashboard hay thông báo là nhu cầu, nhóm tập trung vào việc người dùng không biết số tiền còn lại, thường bỏ qua việc đối chiếu ngân sách và chỉ nhận ra đã vượt mức khi cuối tháng. Những ý tưởng tính năng được đưa ra khỏi phần Opportunity để tránh nhầm lẫn. Qua hoạt động này, tôi hiểu rằng cần xác định nguyên nhân và nhu cầu trước khi lựa chọn công nghệ hoặc tính năng. Một sản phẩm có nhiều chức năng chưa chắc giải quyết đúng vấn đề. Nếu được làm lại, tôi sẽ chú ý phản biện sớm hơn mỗi khi nhóm bắt đầu thảo luận về cách xây dựng sản phẩm mà chưa có đủ bằng chứng về nhu cầu người dùng.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Có. Khi trình bày candidate kiểm tra trạng thái Agent NPC, tôi ban đầu tập trung vào việc phải đối chiếu nhiều nguồn thông tin như /diagnostics, /status, PID và trạng thái module. Tuy nhiên, qua phản biện, tôi nhận ra cần làm rõ giá trị của vấn đề so với những công cụ có sẵn như health check, logging và monitoring. Một nhận xét đáng chú ý là HTTP 200 không đồng nghĩa toàn bộ hệ thống đang hoạt động chính xác. Tôi đồng ý vì trong trải nghiệm kiểm tra dự án, endpoint có thể phản hồi thành công nhưng source parity hoặc trạng thái module vẫn chưa đạt. Vì vậy, tôi làm rõ bottleneck nằm ở bước đối chiếu nhiều nguồn dữ liệu, đồng thời bổ sung các thông tin cần kiểm tra vào success metric. Tôi cũng nhận ra không phải bước nào mất thời gian cũng cần AI giải quyết; những kiểm tra có điều kiện cố định có thể sử dụng script hoặc rule. Candidate của tôi vẫn được đưa vào shortlist và đạt 29/35 điểm, nhưng nhóm cuối cùng chọn quản lý chi tiêu với 34/35 điểm. Điều này giúp tôi hiểu rằng cần đánh giá vấn đề theo nhu cầu và tác động thay vì chỉ dựa vào kinh nghiệm kỹ thuật của bản thân.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Điều khiến tôi chú ý là trường hợp người dùng bỏ ghi chép chi tiêu thủ công sau bốn ngày được đề cập trong kết quả phỏng vấn của nhóm. Tôi không trực tiếp thực hiện phần CP4 nên không xem đây là dữ liệu do mình thu thập, nhưng thông tin này giúp tôi hiểu rõ hơn khó khăn của phương án ghi chép thủ công. Ban đầu, tôi nghĩ người dùng có thể sử dụng bảng tính để nhập các khoản chi và tự tính số dư ngân sách. Tuy nhiên, nếu người dùng không duy trì việc nhập dữ liệu thì hệ thống sẽ thiếu thông tin và kết quả tính toán không còn chính xác. Tôi nhận ra vấn đề không chỉ nằm ở phép tính mà còn ở việc duy trì thói quen sử dụng. Dù vậy, việc bỏ ghi chép sau bốn ngày chưa đủ chứng minh rằng AI chắc chắn là giải pháp tốt hơn. Nhóm vẫn cần kiểm tra thêm khả năng nhận thông báo giao dịch, độ chính xác phân loại và mức độ sẵn sàng cấp quyền của người dùng. Qua đó, tôi hiểu rằng kết quả kiểm chứng cần được đánh giá đúng phạm vi, không nên suy rộng từ một trường hợp thành kết luận cho tất cả người dùng.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Theo tôi, điều khó nhất khi viết Problem Statement là xác định đúng vấn đề mà không đưa giải pháp vào quá sớm. Với candidate quản lý chi tiêu, nếu viết người dùng cần một ứng dụng tự động phân loại giao dịch thì nội dung đã chuyển sang mô tả sản phẩm. Vấn đề thực tế cần thể hiện người dùng khó theo dõi các khoản chi nhỏ, không biết số dư ngân sách và thường phát hiện vượt ngân sách quá muộn. Ngoài ra, việc xác định bottleneck và success metric cũng không đơn giản vì cần phân biệt dữ liệu đã có với mục tiêu đề xuất. Ví dụ, thời gian tiết kiệm hoặc tỷ lệ phân loại chính xác chưa thể xem là kết quả thực tế khi nhóm chưa triển khai pilot. Tôi cũng nhận thấy cần xác định boundary để AI không vượt quá vai trò hỗ trợ, đặc biệt với dữ liệu tài chính cá nhân. Người dùng vẫn phải có quyền xác nhận và sửa giao dịch. Qua bài tập, tôi hiểu Problem Statement cần ngắn gọn nhưng phải thể hiện được Actor, quy trình, khó khăn, tác động và kết quả mong muốn. Nếu mô tả quá rộng thì khó triển khai và đánh giá, còn nếu đưa tính năng vào quá sớm thì có thể khiến nhóm giải quyết sai vấn đề.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Nếu làm lại, tôi sẽ chuẩn bị bằng chứng cụ thể hơn cho các candidate của mình, đặc biệt là thời gian thực hiện từng bước. Những số liệu như 8–12 phút kiểm tra Git hay 20–30 phút kiểm tra Agent NPC hiện mới là ước tính, chưa được đo bằng đồng hồ. Tôi sẽ ghi lại thời gian qua nhiều lần thực hiện để có baseline đáng tin cậy hơn. Khi phản biện các thành viên khác, tôi cũng sẽ hỏi sâu hơn về lần gần nhất họ gặp vấn đề, cách xử lý hiện tại và hậu quả thực tế thay vì chỉ hỏi về ý tưởng sản phẩm. Với candidate quản lý chi tiêu, tôi muốn nhóm làm rõ người dùng có thực sự muốn tự động nhận thông báo giao dịch hay không, vì việc cấp quyền truy cập dữ liệu tài chính cũng có những rủi ro riêng. Tôi cũng sẽ đặt câu hỏi AI có tạo ra giá trị gì so với rule và các ứng dụng quản lý chi tiêu hiện có. Ngoài ra, tôi sẽ chú ý phân biệt trải nghiệm cá nhân với bằng chứng từ nhiều người dùng. Qua đó, tôi muốn việc lựa chọn problem có cơ sở rõ ràng hơn, tránh chọn một vấn đề chỉ vì bản thân thấy thú vị hoặc có thể xây dựng được về mặt kỹ thuật.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.
Theo tôi hiểu, bài toán nhóm chọn là giúp người dùng quản lý tiền ăn uống tốt hơn vì nhiều khi có những khoản chi nhỏ nên dễ quên và không biết mình còn bao nhiêu tiền. Khi có thông báo giao dịch, AI sẽ đọc nội dung và đoán xem đó có phải khoản ăn uống không. Sau đó, hệ thống sẽ cộng tiền đã chi, tính số tiền còn lại và đưa ra cảnh báo nếu gần hết ngân sách. Nhóm sẽ đánh giá kết quả qua việc người dùng có giảm vượt ngân sách không và AI phân loại có chính xác không. Tuy nhiên, AI không được tự quyết định người dùng có nên mua đồ hay không, người dùng vẫn phải tự xác nhận hoặc sửa nếu AI phân loại sai. Nhóm chọn Workflow thay vì Agent vì các bước xử lý khá đơn giản và cố định, chưa cần một AI tự chủ động làm nhiều việc. Nói chung, AI chỉ đóng vai trò hỗ trợ để người dùng dễ kiểm soát tiền hơn, còn quyết định cuối cùng vẫn là của người dùng.

---

## 7. Tài liệu tham khảo

- Tài liệu lab: docs/01-worksheet.md, docs/03-international-frameworks.md
- Money Lover: https://moneylover.me/vi
- Timo (Hũ Chi Tiêu): https://timo.vn/
- YNAB: https://www.ynab.com/
