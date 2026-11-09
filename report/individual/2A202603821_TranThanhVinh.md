# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Trần Thành Vinh
- MSSV: 2A202603821
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: Alpha
- Link repo nhóm: https://github.com/xrkhanhlinh/K5-L3B-Day02-Alpha-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại + Stakeholder Pain | Khi phản hồi của cư dân cần được giải quyết thì cần phải có 1 người thậm chí 1 ban đọc và giải quyết (nếu được) hoặc phân loại report cho người khác giải quyết | Các cư dân, ban quản lý tòa nhà | rút ngắn thời gian (10 phút -> 2 phút), tiết kiệm nhân công. |
| 2 | Lặp lại + AI làm tốt hơn | Trong một dây chuyền, để kiểm soát chất lượng của một sản phẩm, thông thường cần 1 hoặc nhiều giám sát. AI sẽ giúp giảm bớt hoặc lược bỏ để những người giám sát làm việc khác | Người giám sát, công ty | Giảm bớt nhân công, tối ưu chi phí |
| 3 | Lặp lại + Tốn thời gian | Khi hồ sơ y tế cần được giải quyết thì cần phải có 1 người thậm chí 1 ban đọc và giải quyết (nếu được) hoặc phân loại cho bác sĩ. Dĩ nhiên các trường hợp urgent sẽ phải lập tức cho con người giải quyết | Người bệnh, bác sĩ, người điều phối | Giảm thời gian |
| 4 | Stakeholder pain | Khi một phương tiện được mang đến xưởng sản xuất để sửa chữa, cần có các nhiều người thợ hỗ trợ để sửa được | Thợ sửa chữa, công ty | Tối ưu chi phí, giảm thời gian |
| 5 | Stakeholder pain | Khi một người đặt xe XanhSM đến điểm bất kì, hệ thống sẽ gặp khó trong việc quyết định điểm đón theo mô tả của tài xế. | Tài xế, người dùng | Giảm thời gian |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- Mình giữ lại tất cả ý của AI và của mình

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | VinFast – AI Visual Quality Inspection: Sử dụng Computer Vision để kiểm tra chất lượng sản phẩm trên dây chuyền sản xuất. | Quy trình lặp lại với số lượng sản phẩm lớn; kiểm tra thủ công phụ thuộc vào sự tập trung của nhân viên và có thể bỏ sót lỗi. AI có khả năng phân tích hình ảnh liên tục, phát hiện và khoanh vùng khuyết điểm. | Số lượng sản phẩm cần kiểm tra, quy trình của họ mình được can thiệp (đặt camera ở những đâu), quy trình sản phẩm. |
| 2 | Vinmec – AI Medical Document Processing & Triage Support: Đọc, tổng hợp và phân loại hồ sơ y tế để hỗ trợ điều phối bác sĩ. | Hồ sơ y tế thường chứa nhiều thông tin và tài liệu khác nhau. Nhân viên phải đọc, tổng hợp và chuyển thông tin đến đúng bộ phận. AI có khả năng xử lý dữ liệu phi cấu trúc, hỗ trợ giảm thời gian hành chính. | Chưa biết số lượng hồ sơ mỗi ngày, thời gian xử lý trung bình, các loại hồ sơ phổ biến và quy trình phân loại trường hợp khẩn cấp hiện tại. |
| 3 | Vinhomes – AI Resident Feedback Processing: Tự động đọc, hiểu và phân loại phản ánh của cư dân để đề xuất hướng xử lý hoặc chuyển đến bộ phận phụ trách. | Đây là công việc lặp lại, có thể phát sinh hàng ngày và cần nhân viên đọc, hiểu nội dung trước khi chuyển tiếp. AI có thể hiểu ngôn ngữ tự nhiên, phân loại những phản ánh không theo mẫu cố định và tổng hợp nhiều thông tin. | Chưa biết số lượng phản ánh mỗi tháng, tỷ lệ phân loại sai, số lần chuyển nhầm bộ phận và thời gian xử lý thực tế. |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi sản phẩm đi qua dây chuyền sản xuất, tôi muốn AI tự động phân tích hình ảnh sản phẩm để phát hiện, phân loại và khoanh vùng các khuyết điểm, nhằm giảm thời gian kiểm tra thủ công, hạn chế bỏ sót lỗi và giúp nhân viên giám sát tập trung vào những công việc quan trọng hơn. |
| Actor | Nhân viên kiểm soát chất lượng (QC), nhân viên giám sát dây chuyền, kỹ sư sản xuất và quản lý nhà máy VinFast. |
| Thời điểm / bối cảnh | Khi sản phẩm đi qua các công đoạn kiểm tra chất lượng trên dây chuyền sản xuất, đặc biệt tại các công đoạn cần quan sát bề mặt, hình dáng, linh kiện hoặc sự hoàn thiện của sản phẩm. |
| Quy trình hiện tại (3–7 bước) | 
1. Sản phẩm được đưa đến vị trí kiểm tra trên dây chuyền. 
2. Nhân viên quan sát sản phẩm trực tiếp hoặc thông qua camera. 
3. Nhân viên đối chiếu sản phẩm với tiêu chuẩn chất lượng. 
4. Nếu phát hiện lỗi, nhân viên đánh dấu và ghi nhận loại lỗi. 
5. Sản phẩm lỗi được chuyển đến bộ phận xử lý hoặc sửa chữa. 
6. Nhân viên tiếp tục kiểm tra các sản phẩm tiếp theo. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 và 3: Nhân viên phải quan sát và đối chiếu từng sản phẩm. Đây là công việc lặp lại, cần sự tập trung liên tục. Giả định ban đầu: 30–60 giây/sản phẩm, tùy loại sản phẩm và tiêu chuẩn kiểm tra. |
| Impact (nếu không giải thì sao) | ốn nhân lực cho công việc kiểm tra lặp lại; hiệu suất kiểm tra có thể bị ảnh hưởng bởi sự mệt mỏi và mức độ tập trung; các lỗi nhỏ có thể bị bỏ sót, dẫn đến chi phí sửa chữa hoặc xử lý sản phẩm lỗi ở công đoạn sau. |
| Success metric (baseline → target) | - Thời gian kiểm tra: giả định 30–60 giây/sản phẩm → mục tiêu 5–10 giây cho bước phân tích tự động. 
 - Tỷ lệ phát hiện lỗi: đo baseline thực tế → mục tiêu Recall tối thiểu 98% đối với nhóm lỗi nghiêm trọng trong pilot. 
 - Tỷ lệ cảnh báo sai: đo baseline → giảm dần qua quá trình huấn luyện và hiệu chỉnh. 
 - Số sản phẩm cần nhân viên kiểm tra trực tiếp: giảm tỷ lệ kiểm tra thủ công toàn bộ, chuyển sang kiểm tra các trường hợp AI không chắc chắn và lấy mẫu kiểm định. |
| Phương án không dùng AI | Sử dụng checklist chất lượng, khuôn đo, thiết bị cảm biến, camera kết hợp với quy tắc so sánh kích thước hoặc ngưỡng cố định. Có thể tăng số lượng nhân viên giám sát hoặc cải tiến quy trình kiểm tra. Tuy nhiên, các quy tắc cố định khó xử lý toàn bộ biến thể khuyết điểm về hình dạng, màu sắc và bề mặt. |
| Giả thuyết về AI (nếu có) | Sử dụng Computer Vision để phân tích hình ảnh sản phẩm, phát hiện và khoanh vùng lỗi. Có thể sử dụng CNN, Vision Transformer hoặc các mô hình Object Detection/Segmentation. AI học từ hình ảnh sản phẩm đạt chuẩn và sản phẩm có lỗi để nhận diện những khuyết điểm phức tạp. Khi độ tin cậy thấp, hệ thống chuyển hình ảnh cho nhân viên QC xác nhận. |
| Cảm nhận nhanh | AI Workflow |

Quy trình nháp hiện tại:

```text
Sản phẩm đi qua dây chuyền
          |
          v
Nhân viên QC quan sát sản phẩm
          |
          v
Đối chiếu với tiêu chuẩn chất lượng
          |
          v
Phát hiện lỗi?
     /         \
   Có           Không
   |              |
   v              v
Ghi nhận lỗi    Cho phép đi
   |            sang công đoạn
   v              tiếp theo
Chuyển bộ phận
xử lý / sửa chữa
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi hồ sơ y tế được tiếp nhận, tôi muốn AI có thể đọc, tổng hợp thông tin quan trọng và phân loại hồ sơ theo chuyên khoa hoặc mục đích xử lý, nhằm giảm thời gian đọc tài liệu thủ công và hỗ trợ chuyển hồ sơ đến đúng bác sĩ hoặc bộ phận phụ trách. Các trường hợp có dấu hiệu khẩn cấp phải được ưu tiên chuyển ngay cho nhân viên y tế. |
| Actor | Nhân viên tiếp nhận bệnh nhân, nhân viên điều phối, bác sĩ, điều dưỡng và bộ phận quản lý hồ sơ Vinmec. |
| Thời điểm / bối cảnh | Khi bệnh viện tiếp nhận hồ sơ khám chữa bệnh, hồ sơ chuyển viện, kết quả xét nghiệm hoặc các tài liệu y tế cần được đọc và tổng hợp trước khi chuyển đến bác sĩ hoặc chuyên khoa liên quan. |
| Quy trình hiện tại (3–7 bước) | 

1. Bệnh nhân hoặc nhân viên cung cấp hồ sơ y tế. 
2. Nhân viên tiếp nhận kiểm tra tính đầy đủ của tài liệu. 
3. Nhân viên đọc các tài liệu và xác định thông tin quan trọng. 
4. Tổng hợp thông tin bệnh nhân, tiền sử và các kết quả liên quan. 
5. Phân loại hồ sơ theo chuyên khoa hoặc mục đích xử lý. 
6. Chuyển hồ sơ đến bác sĩ hoặc bộ phận phù hợp. 
7. Nếu có dấu hiệu khẩn cấp, báo ngay cho nhân viên y tế theo quy trình hiện hành. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2, 3 và 4: Nhân viên phải đọc nhiều tài liệu, đôi khi ở nhiều định dạng khác nhau, rồi tổng hợp thông tin. Giả định ban đầu: 10–15 phút/hồ sơ, cần xác minh qua phỏng vấn nhân viên tiếp nhận. |
| Impact (nếu không giải thì sao) | Tăng thời gian xử lý hành chính; hồ sơ có thể bị chuyển chậm hoặc sai bộ phận; nhân viên phải đọc lại thông tin đã xuất hiện trong nhiều tài liệu; bệnh nhân phải chờ lâu hơn trước khi được điều phối đến bộ phận phù hợp. |
| Success metric (baseline → target) | - Thời gian đọc và tổng hợp hồ sơ: giả định 10–15 phút → mục tiêu 3–5 phút cho bước hỗ trợ xử lý. 
 - Tỷ lệ trích xuất chính xác thông tin: đo baseline → cải thiện theo từng nhóm tài liệu. 
 - Tỷ lệ phân loại hồ sơ đúng chuyên khoa: đo baseline → mục tiêu tối thiểu 95% trong pilot, có nhân viên xác nhận. 
 - Thời gian chuyển hồ sơ đến bộ phận phù hợp: đo baseline → giảm ít nhất 30% trong pilot. 
 - 100% trường hợp khẩn cấp được xử lý theo quy trình ưu tiên của bệnh viện, không chờ AI hoàn tất xử lý thông thường. |
| Phương án không dùng AI | Chuẩn hóa biểu mẫu hồ sơ, yêu cầu bệnh nhân điền thông tin theo cấu trúc cố định, sử dụng nhân viên chuyên trách để kiểm tra và phân loại. Có thể sử dụng OCR truyền thống và các quy tắc cố định để trích xuất một số trường dữ liệu. Tuy nhiên, cách này hạn chế khi hồ sơ không đồng nhất, có nhiều định dạng và cần tổng hợp thông tin từ nhiều tài liệu. |
| Giả thuyết về AI (nếu có) | Sử dụng OCR/Document AI để đọc tài liệu; LLM để trích xuất, tóm tắt và tổng hợp thông tin từ nhiều nguồn; RAG hỗ trợ tra cứu quy định và quy trình tiếp nhận; AI classification để đề xuất chuyên khoa hoặc bộ phận tiếp nhận. Các dấu hiệu cần ưu tiên được nhận diện để cảnh báo nhân viên, nhưng quyết định phân loại mức độ khẩn cấp và xử lý chuyên môn phải tuân theo quy trình của bệnh viện và có nhân viên y tế chịu trách nhiệm. |
| Cảm nhận nhanh | Agent + Workflow |

Quy trình nháp hiện tại:

```text
Bệnh nhân cung cấp hồ sơ
          |
          v
Nhân viên tiếp nhận hồ sơ
          |
          v
Kiểm tra tính đầy đủ
          |
          v
Đọc và tổng hợp thông tin
          |
          v
Phân loại hồ sơ
          |
          v
Chuyển bác sĩ / chuyên khoa
          |
          v
Bác sĩ tiếp nhận và xử lý
```

Nhánh xử lý đặc biệt:
```text
Tiếp nhận hồ sơ hoặc thông tin bệnh nhân
          |
          v
Phát hiện dấu hiệu cần xử lý khẩn cấp?
          |
          v
Chuyển ngay cho nhân viên y tế
theo quy trình ưu tiên của bệnh viện
```

Quy trình có AI:
```text
Bệnh nhân cung cấp hồ sơ
          |
          v
OCR / Document AI đọc tài liệu
          |
          v
LLM tổng hợp thông tin quan trọng
          |
          v
AI đề xuất phân loại hồ sơ
          |
          v
Có dấu hiệu cần ưu tiên?
     /              \
   Có                Không
   |                   |
   v                   v
Cảnh báo nhân viên   Đề xuất chuyên khoa
y tế ngay            hoặc bộ phận xử lý
   |                   |
   v                   v
Nhân viên y tế xác nhận / điều phối
          |
          v
Bác sĩ tiếp nhận và xử lý
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi cư dân gửi phản ánh hoặc yêu cầu hỗ trợ, tôi muốn AI có khả năng đọc, hiểu nội dung, phân loại vấn đề và đề xuất hướng giải quyết hoặc chuyển report đến đúng bộ phận phụ trách, nhằm rút ngắn thời gian tiếp nhận và giảm công việc đọc, phân loại thủ công của ban quản lý. |
| Actor | Cư dân, nhân viên CSKH, lễ tân, ban quản lý tòa nhà và các bộ phận kỹ thuật, vệ sinh, an ninh tại Vinhomes. |
| Thời điểm / bối cảnh | Khi cư dân gửi phản ánh thông qua ứng dụng, hotline, email hoặc các kênh tiếp nhận khác. Ví dụ: phản ánh thang máy hỏng, nước bị rò rỉ, tiếng ồn, vệ sinh khu vực chung hoặc sự cố an ninh. |
| Quy trình hiện tại (3–7 bước) | 1. Cư dân gửi phản ánh qua một kênh tiếp nhận. 
 2. Nhân viên CSKH hoặc ban quản lý đọc nội dung phản ánh. 
 3. Nhân viên xác định vấn đề, địa điểm và mức độ ưu tiên. 
 4. Tìm bộ phận có trách nhiệm xử lý. 
 5. Tạo report hoặc chuyển nội dung đến bộ phận đó. 
 6. Theo dõi tình trạng xử lý và phản hồi cư dân. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2, 3 và 4: Nhân viên phải đọc và hiểu nội dung bằng ngôn ngữ tự nhiên, xác định đúng loại vấn đề và tìm bộ phận phụ trách. Giả định ban đầu: 10 phút/report → mục tiêu 2 phút cho bước tiếp nhận, phân loại và định tuyến. |
| Impact (nếu không giải thì sao) | Nhân viên mất nhiều thời gian cho công việc tiếp nhận lặp lại; phản ánh có thể được chuyển sai bộ phận; phải trao đổi và chuyển tiếp nhiều lần; cư dân phải chờ lâu hơn và có thể gửi phản ánh nhiều lần do chưa nhận được phản hồi. |
| Success metric (baseline → target) | - Thời gian tiếp nhận, phân loại và chuyển report: 10 phút → 2 phút. 
 - Tỷ lệ chuyển đúng bộ phận ngay lần đầu: đo baseline → mục tiêu từ 90% trong pilot. 
 - Tỷ lệ report phải chuyển lại do sai bộ phận: giảm ít nhất 50% so với baseline. 
 - Thời gian từ lúc nhận phản ánh đến lúc có người phụ trách: giảm ít nhất 30%. 
 - Tỷ lệ phản ánh bị bỏ sót: theo dõi và giảm so với quy trình hiện tại. |
| Phương án không dùng AI | Xây dựng biểu mẫu phản ánh có các trường bắt buộc, sử dụng danh sách danh mục vấn đề cố định và quy tắc IF-ELSE để chuyển report đến bộ phận tương ứng. Bổ sung nhân viên trực tiếp đọc và phân loại những trường hợp không đúng mẫu. Tuy nhiên, cách này khó xử lý các phản ánh có nội dung tự do, nhiều vấn đề trong một report hoặc cách diễn đạt không thống nhất. |
| Giả thuyết về AI (nếu có) | Sử dụng LLM để hiểu nội dung phản ánh bằng ngôn ngữ tự nhiên, nhận diện vấn đề, địa điểm và mức độ ưu tiên; kết hợp RAG để tra cứu quy trình xử lý và các trường hợp tương tự; AI đề xuất bộ phận phụ trách, tạo bản tóm tắt và chuyển thành ticket. Các report có mức độ nghiêm trọng cao hoặc độ tin cậy thấp sẽ được chuyển cho nhân viên xác nhận. |
| Cảm nhận nhanh | Agent + Workflow |

Quy trình nháp hiện tại:

```text
Cư dân gửi phản ánh
          |
          v
Nhân viên CSKH tiếp nhận
          |
          v
Đọc và hiểu nội dung report
          |
          v
Phân loại vấn đề
          |
          v
Xác định bộ phận phụ trách
          |
          v
Chuyển report đến bộ phận đó
          |
          v
Theo dõi và phản hồi cư dân
```

Quy trình có AI:
```text 
Cư dân gửi phản ánh
          |
          v
AI tiếp nhận nội dung
          |
          v
LLM hiểu và phân loại report
          |
          v
RAG tra cứu quy trình xử lý
          |
          v
AI đề xuất bộ phận phụ trách
          |
          v
Độ tin cậy đủ cao?
      /          \
    Có            Không
    |               |
    v               v
Tạo ticket       Chuyển nhân viên
và định tuyến    kiểm tra
    |               |
    v               v
Bộ phận phụ trách tiếp nhận
          |
          v
Xử lý và phản hồi cư dân
```

### Card muốn pitch nhất

- Card số: 1
- Vì sao:

Đây là quy trình lặp lại với số lượng sản phẩm lớn, đòi hỏi nhân viên QC phải quan sát và kiểm tra liên tục. Điều này có thể gây tốn nhân lực và ảnh hưởng đến độ ổn định khi kiểm tra.

Bài toán có đầu vào và đầu ra tương đối rõ ràng: hình ảnh sản phẩm → phát hiện, phân loại và khoanh vùng khuyết điểm → cảnh báo hoặc chuyển cho nhân viên QC.

Computer Vision có khả năng phân tích hình ảnh liên tục, hỗ trợ phát hiện các khuyết điểm phức tạp trên bề mặt sản phẩm mà việc xây dựng các quy tắc cố định có thể gặp khó khăn.

Có thể đo lường hiệu quả tương đối rõ thông qua thời gian kiểm tra, tỷ lệ phát hiện lỗi, tỷ lệ cảnh báo sai và chi phí kiểm soát chất lượng.

Có tiềm năng mở rộng sang nhiều công đoạn kiểm tra khác nhau nếu thử nghiệm ban đầu thành công.

- Câu hỏi muốn nhóm phản biện:

Bài toán này có thực sự cần AI hay chỉ cần camera kết hợp với Image Processing và các thuật toán Computer Vision truyền thống?

Nếu AI bỏ sót một lỗi nghiêm trọng thì hậu quả và chi phí phát sinh sẽ như thế nào? Có nên để AI tự quyết định sản phẩm đạt chuẩn hay vẫn cần nhân viên QC xác nhận?

Chi phí xây dựng, triển khai và bảo trì hệ thống camera, mô hình AI có thực sự thấp hơn chi phí kiểm tra thủ công không?

Làm thế nào để AI phát hiện những lỗi hiếm, chưa từng xuất hiện trong dữ liệu huấn luyện?

Liệu hệ thống có hoạt động ổn định khi thay đổi ánh sáng, góc chụp, màu sắc sản phẩm hoặc dây chuyền sản xuất không?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
| Các lỗi nghiêm trọng thường xuất hiện với tần suất thấp nên dữ liệu huấn luyện có thể mất cân bằng. Ngoài ra, việc thu thập và gán nhãn hình ảnh lỗi đòi hỏi chuyên môn của nhân viên QC. | Đồng ý | Chuyển hướng bài toán từ classification thành Anomaly Detection |
| Việc giảm thời gian phân tích hình ảnh không đồng nghĩa với việc giảm tương ứng số lượng nhân viên. Hệ thống vẫn cần người giám sát, xử lý ngoại lệ và kiểm tra các cảnh báo. | Không đồng ý | Chắc chắn số người cần để vận hành hệ thống trên sẽ giảm bớt bởi chỉ cần 1-2 thợ giỏi quan sát quá trình từ đầu đến cuối thông qua camera. Bản thân dây chuyền không AI đã hoạt động tốt hơn là chỉ sử dụng nhân công thường |

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
