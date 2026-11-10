# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: Alpha
- Candidate problem nhóm chọn (1 câu): Khi thu nhập về không đều và tiền nằm ở nhiều nguồn, học viên làm freelance/part-time khó đối soát giao dịch và tính lại ngân sách theo tiền thực có để biết mức chi phù hợp trong kỳ rà soát, làm tăng nguy cơ hụt tiền cho các khoản thiết yếu.
- Quyết định cuối (Go / Not Yet / No-Go): **Not Yet** — theo bản tổng hợp hiện tại, cần kiểm chứng thêm nhu cầu, chất lượng dữ liệu và lợi ích so với Rule/công cụ có sẵn trước khi triển khai AI.

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Nguyễn Thị Khánh Linh | 2A202603845 | Tổng hợp báo cáo nhóm, phân tích đối soát giao dịch, rà soát Problem Statement và mức can thiệp AI; quản lý repo chung | [xrkhanhlinh](https://github.com/xrkhanhlinh) |
| 2 | Đỗ Thị Thu Hằng | 2A202603840 | Phản biện điểm khác biệt, phân tích quản lý tiền đa nguồn, góp ý Problem Statement và boundary | Chưa xác nhận username; tên tác giả commit: `ThuHang2604` |
| 3 | Trần Thành Vinh | 2A202603821 | Phân tích candidate chuyên môn, chuẩn bị sơ đồ quy trình, góp ý phạm vi ứng dụng AI | Chưa xác nhận username; tên tác giả commit: `Vinh` |
| 4 | Vũ Ngọc Quỳnh Anh | 2A202603875 | Đề xuất candidate thu nhập không đều, xây dựng giả định, thực hiện survey và research giải pháp tương tự | Chưa xác nhận username; tên tác giả commit: `Anne` |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Nguyễn Thị Khánh Linh | Đỗ Thị Thu Hằng, Trần Thành Vinh, Vũ Ngọc Quỳnh Anh | Cluster, cây OST, bảng chấm điểm — `group_report.md` mục 2 |
| CP4 — Kiểm chứng | Vũ Ngọc Quỳnh Anh | Nguyễn Thị Khánh Linh, Đỗ Thị Thu Hằng | Assumption map, survey 6 người và ảnh kết quả — `group_report.md` mục 3.1–3.2; `report/assets/cp4-survey-1.png`, `cp4-survey-2.png` |
| CP4 — Research | Vũ Ngọc Quỳnh Anh | Đỗ Thị Thu Hằng, Nguyễn Thị Khánh Linh | Bảng research có link, đối chiếu Money Lover, YNAB và Splitwise — `group_report.md` mục 3.3 |
| CP5 — Quy trình trước/sau | Trần Thành Vinh | Vũ Ngọc Quỳnh Anh, Nguyễn Thị Khánh Linh, Đỗ Thị Thu Hằng | Quy trình + bảng before/after — `group_report.md` mục 4; ảnh quy trình trong `report/assets/` |
| CP5 — Problem Statement v0 | Đỗ Thị Thu Hằng | Nguyễn Thị Khánh Linh, Vũ Ngọc Quỳnh Anh | Problem Statement v0, actor, bottleneck, metric và boundary — `group_report.md` mục 5 |
| CP6 — Mức can thiệp + Problem Statement v1 | Nguyễn Thị Khánh Linh | Vũ Ngọc Quỳnh Anh, Đỗ Thị Thu Hằng, Trần Thành Vinh | Ma trận, AI Canvas, eval, Problem Statement v1; đối chiếu Rule/Workflow/Agent — `group_report.md` mục 6–7 |
| CP6 — Quyết định | Nguyễn Thị Khánh Linh | Đỗ Thị Thu Hằng, Trần Thành Vinh, Vũ Ngọc Quỳnh Anh | 4 rủi ro + đề xuất Not Yet, điều kiện kiểm chứng và ngưỡng dừng — `group_report.md` mục 8 |

Phân công trên được tổng hợp từ phần việc đã ghi trong báo cáo cá nhân, nội dung hiện có và lịch sử commit; người chính là đầu mối đề xuất để rà soát sản phẩm, không thay thế biên bản phân công đã được nhóm xác nhận. Điểm shortlist, lựa chọn Workflow và quyết định Not Yet trong báo cáo nhóm vẫn cần cả nhóm xác nhận.

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### NguyenThiKhanhLinh-2A202603845

**Phần việc phụ trách:**

- Tổng hợp báo cáo cá nhân thành báo cáo chung của nhóm Alpha và quản lý nội dung trên repo chung.
- Phân tích bước đối soát giao dịch, đặc biệt là chi hộ, hoàn tiền và nội dung không rõ ràng.
- Rà soát Problem Statement, success metric, boundary và lập luận lựa chọn mức can thiệp AI.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Xây dựng 3 Problem Cards về quy trình nghiên cứu protein–protein, lỗi lặp lại sau góp ý và thông tin học tập/công việc phân tán; nêu các điểm cần kiểm chứng trước khi chọn AI.
- Tham gia tổng hợp các candidate, phân nhóm pain và thu hẹp hướng bài toán tài chính; góp ý tập trung vào phân loại và đối soát giao dịch thay vì mô tả một ứng dụng quản lý tài chính quá rộng.
- Phân tích phương án Rule xử lý trường hợp rõ ràng, AI hỗ trợ nội dung mơ hồ và người dùng xác nhận; đề xuất Workflow có kiểm soát thay vì tự động hóa toàn bộ.
- Tổng hợp nội dung CP3–CP6 vào `report/team/group_report.md`, gồm cluster, OST, shortlist, giả định, research, quy trình trước/sau, Problem Statement v0/v1, tiêu chí đánh giá và quyết định. Phần suy luận bổ sung được phân biệt với bằng chứng đã có.
- Đề xuất Not Yet khi chưa đủ bằng chứng về nhu cầu, độ chính xác và lợi ích riêng của AI; giữ quyền quyết định tài chính cho người dùng.
- Gộp cập nhật của các thành viên vào `main`, xử lý xung đột `TEAM.md` để giữ đầy đủ phần đóng góp của các bên và bổ sung kết quả survey mới vào bản chung qua merge.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- [Báo cáo cá nhân](report/individual/2A202603845_NguyenThiKhanhLinh.md): mục 3 (3 Problem Cards), mục 4 (đóng góp nhóm), mục 5 (dùng AI) và mục 6.7 (chuỗi lập luận bài nhóm).
- [Báo cáo nhóm](report/team/group_report.md): mục 2.1, dòng #1–#3; mục 2.2 (pain đối soát); mục 4–7 (quy trình, Problem Statement, mức AI); mục 8 (Not Yet và ngưỡng dừng).
- Commit `20d61d6`: cập nhật báo cáo cá nhân của Khánh Linh; `524478a`: hoàn thiện bản tổng hợp báo cáo nhóm.
- Commit `6986d1a`, `049eb8c`, `6c0ae92`: gộp các nhánh của thành viên; `dc84821`: gộp cập nhật mới, giữ phần đóng góp của các thành viên và kết quả khảo sát.

**Điều mình học được từ phần nhóm:**

- Một ý tưởng công nghệ hấp dẫn chưa đủ để trở thành vấn đề ưu tiên; cần làm rõ actor, hành vi hiện tại, bottleneck và bằng chứng về pain.
- Cần so sánh No AI, Rule và Workflow trước khi lựa chọn mức can thiệp; chỉ dùng AI tại bước tạo thêm giá trị và vẫn kiểm chứng được đầu ra.
- Metric phải có baseline và cách đo; không dùng số liệu AI suy đoán như kết quả thực nghiệm. Với bài toán tài chính, cần xác định dữ liệu đầu vào, hậu quả khi AI sai và người chịu trách nhiệm kiểm tra.
- Nếu làm lại, tôi sẽ ưu tiên kiểm chứng nhu cầu sớm hơn, đặt câu hỏi rõ hơn về chi phí, độ chính xác và giới hạn quyền của AI trước khi quyết định triển khai.

### DoThiThuHang-2A202603840

**Phần việc phụ trách:**

Tham gia xây dựng và hoàn thiện nội dung báo cáo nhóm, tập trung vào các hoạt động từ CP2 đến CP7.
Phân tích, lựa chọn và đánh giá các Problem Cards dựa trên tính thực tế, mức độ cần thiết và khả năng triển khai giải pháp.
Tham gia đề xuất giải pháp ứng dụng AI hỗ trợ quản lý tài chính cá nhân.
**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

Xây dựng và sắp xếp Top 3 Problem Cards tại CP2, giải thích lý do lựa chọn và xác định những điểm còn chưa chắc chắn cần kiểm chứng.
Hoàn thiện nội dung phần 4 về những hoạt động và đóng góp cá nhân trong quá trình thực hiện CP3–CP7.
Tham gia bổ sung, chỉnh sửa nội dung báo cáo tại phần 5 và phần 6, đảm bảo nội dung có tính liên kết và thống nhất với định hướng của nhóm.
Phân tích và hoàn thiện câu 6.7 về giải pháp AI hỗ trợ quản lý tài chính cá nhân, tập trung vào việc tổng hợp số dư từ nhiều nguồn như tài khoản ngân hàng, ví điện tử và tiền mặt; theo dõi chi tiêu, đối soát giao dịch và đưa ra cảnh báo, gợi ý tiết kiệm.
**Bằng chứng** (phần nào trong group_report.md, file nào trong report/assets/, commit nào):

[Báo cáo cá nhân của Thu Hằng](report/individual/2A202603840_DoThiThuHang.md): mục 3 (Top 3 Problem Cards), mục 4–6 (đóng góp nhóm, dùng AI và reflection), mục 6.7 (giải thích bài nhóm).
[Báo cáo nhóm](report/team/group_report.md): mục 2.1, dòng #4–#6; mục 2.4 (phản biện điểm khác biệt); mục 4–5 (quy trình đa nguồn và Problem Statement); mục 6.4 (người dùng giữ quyền quyết định).
Commit `7c05f90`: cập nhật báo cáo cá nhân; `5559c0d`: thêm phần đóng góp của Thu Hằng vào `TEAM.md`.

**Điều mình học được từ phần nhóm:**

Biết cách xác định và đánh giá vấn đề thực tế dựa trên mức độ ảnh hưởng, tính cấp thiết và khả năng triển khai thay vì chỉ lựa chọn những ý tưởng có vẻ hấp dẫn.
Hiểu rõ hơn cách ứng dụng AI vào giải quyết vấn đề đời sống, đặc biệt là hỗ trợ phân tích dữ liệu tài chính, theo dõi chi tiêu và đưa ra gợi ý phù hợp.
Nhận ra rằng AI nên đóng vai trò trợ lý phân tích và hỗ trợ ra quyết định, không nên tự ý thực hiện các giao dịch tài chính thay cho người dùng.
Rèn luyện kỹ năng làm việc nhóm, tổng hợp ý kiến, hoàn thiện nội dung báo cáo.

### TranThanhVinh-2A202603821

**Phần việc phụ trách:**

Tham gia khảo sát và đánh giá các bài toán ứng dụng AI ở CP1–CP2, tập trung vào các quy trình lặp lại, tốn thời gian và cần đọc/tổng hợp nhiều thông tin.
Xây dựng 3 Problem Cards (VinFast – kiểm tra chất lượng bằng Computer Vision, Vinmec – xử lý hồ sơ y tế, Vinhomes – xử lý phản ánh cư dân) kèm quy trình hiện tại và quy trình có AI.
Chuẩn bị hình ảnh quy trình cho báo cáo nhóm và mô tả hướng bài toán quản lý chi tiêu thông minh của nhóm.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

Quét 5 vấn đề ở CP1 theo các lăng kính Lặp lại, Tốn thời gian, Stakeholder pain.
Chọn và xếp hạng Top 3 Problem Cards ở CP2, nêu lý do chọn và những điểm còn chưa chắc; chọn Card #1 (VinFast) để pitch kèm các câu hỏi cho nhóm phản biện (có thật sự cần AI, hậu quả khi bỏ sót lỗi nặng, chi phí triển khai, lỗi hiếm, thay đổi ánh sáng/góc chụp).
Tiếp nhận phản biện của AI về Card #1: đồng ý chuyển hướng từ classification sang Anomaly Detection do dữ liệu lỗi mất cân bằng; giữ quan điểm về việc giảm nhân lực giám sát.
Hoàn thiện phần Dùng AI (mục 5) và Reflection CP7 (mục 6), gồm câu 6.7 mô tả chuỗi problem → quy trình → metric → mức can thiệp AI của bài nhóm.
Bổ sung ảnh quy trình cp2-workflow-card-1.png và cp5-workflow-future.png vào report/assets/.

**Bằng chứng** (phần nào trong group_report.md, file nào trong report/assets/, commit nào):

[Báo cáo nhóm](report/team/group_report.md): mục 2.1, dòng #7–#9 (3 Card của Thành Vinh); mục 2.4 (lý do tạm hoãn candidate kiểm tra chất lượng); mục 6 (đối chiếu phạm vi hỗ trợ và quyền quyết định).
[Báo cáo cá nhân của Thành Vinh](report/individual/2A202603821_TranThanhVinh.md): toàn bộ mục 1–7; mô tả hướng bài toán tài chính của nhóm ở mục 6.7 của file cá nhân.
Ảnh minh chứng: [quy trình Card #1](report/assets/cp2-workflow-card-1.png), [quy trình tương lai](report/assets/cp5-workflow-future.png).
Commit `c80385c` (CP2), `4a0de07` (CP7), `8be0345` (ai log), `33642ad` (Last minute), `8468951` (Fix table), `c03ded6` (Add photos), `36f91f7` (đóng góp trong `TEAM.md`).

**Điều mình học được từ phần nhóm:**

Biết nhìn vấn đề từ góc độ người dùng và người không làm kỹ thuật, ví dụ các bạn trong nhóm có góc nhìn riêng về lĩnh vực sinh học và tài chính.
Hiểu rằng cần bắt đầu từ vấn đề cụ thể (ai gặp, ở bước nào, mất bao lâu) rồi mới xác định AI can thiệp ở bước nào, thay vì nghĩ giải pháp trước.
Nhận ra AI nên hỗ trợ và có cơ chế chuyển cho người xác nhận khi độ tin cậy thấp hoặc trường hợp nghiêm trọng, thay vì tự quyết định hoàn toàn.
Rèn luyện kỹ năng làm việc nhóm, tổng hợp ý kiến và đo lường vấn đề bằng metric trước/sau.

### VuNgocQuynhAnh-2A202603875
**Phần việc phụ trách:**

- Phụ trách tìm assumptions cho dự án
- Đồng hành cùng các thành viên nghĩ thêm features cho dự án
- Làm survey form

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Nghĩ ra 5 assumptions cho dự án, chọn ra 3 assumptions quan trọng nhất nhưng chưa có nhiều bằng chứng và đưa ra cách kiểm chứng để sản phẩm viable.
- Cùng các thành viên thảo luận thêm các features để giúp sản phẩm có USPs và kế hoạch triển khai sản phẩm khả thi so với các đối thủ cạnh tranh khác.
- Làm survey form trên Google Forms và thu được 6 câu trả lời để ghi nhận tín hiệu ban đầu về nhu cầu kiểm soát ngân sách; mẫu nhỏ chưa đủ chứng minh nhu cầu thị trường hoặc sự cần thiết của AI.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md` mục 2.1 Pitch: dòng #10, #11, #12 là 3 Problem Card của Quỳnh Anh; dòng #7 ghi câu phản biện Quỳnh Anh đặt cho card của Vinh ("target users có phải nhà máy legacy không?").
- `group_report.md` mục 2.4 "Vì sao chọn": nhóm giữ hướng tài chính theo Card #2 của Quỳnh Anh (thu nhập không đều); "Xử lý bất đồng" ghi Quỳnh Anh bảo vệ mức Agent.
- `group_report.md` mục 4.1: quy trình hiện tại 5 giai đoạn được tổng hợp từ quy trình 6 bước trong Card #2 của Quỳnh Anh; bottleneck "tính lại kế hoạch" lấy từ card này.
- `group_report.md` mục 5 (phản biện v0) và 6.4 (Google PAIR): ghi nhận phản biện "khác app sẵn có ở đâu", "không xem số liệu AI đoán là thật" và nguyên tắc giữ quyền quyết định cho người dùng từ báo cáo của Quỳnh Anh.
- `report/assets/cp2-workflow-card-2.png`: sơ đồ quy trình hiện tại của Card #2, có bottleneck và thời gian từng bước.
- `report/assets/cp4-survey-1.png`, `report/assets/cp4-survey-2.png`: kết quả survey 6 người. 5/6 (83,3%) có bật thông báo biến động số dư nhưng "không giúp kiểm soát được"; nhu cầu nhiều nhất là cảnh báo khi sắp vượt budget (4/6), biết ngay còn bao nhiêu so với budget sau mỗi lần trả tiền (3/6) và tự phân loại giao dịch (3/6); 0/6 chọn "không cần gì thêm".
- Báo cáo cá nhân: `report/individual/2A202603875_VuNgocQuynhAnh.md`.
- Commit: `76201a1` (thêm báo cáo cá nhân), `dc22caf` (thêm sơ đồ quy trình Card #2).
- Commit: `6eef33e`, `68c6e0c` (thêm ảnh và tổng hợp kết quả survey vào báo cáo nhóm), `7b4b1b1` (bổ sung bằng chứng đóng góp trong `TEAM.md`).

**Điều mình học được từ phần nhóm:**

- Cần mô tả đúng hoàn cảnh của actor: với bản thân, tiền đến từ freelance, part-time và hỗ trợ gia đình, nên không thể mặc định có lương cố định. Việc sửa actor giúp nhìn rõ hơn pain khi thu nhập không đều.
- Tôi nhận ra mình từng đi từ giải pháp như “personal assistant” hoặc “kiểm soát tài chính tự động” trước khi làm rõ vấn đề; đổi sang câu hỏi “hôm nay tiêu bao nhiêu là phù hợp” giúp tập trung vào bước tính lại kế hoạch.
- Câu hỏi về khác biệt với ứng dụng có sẵn buộc tôi tìm hiểu đối thủ và thu hẹp phạm vi; nhận định từ research vẫn cần kiểm tra nguồn và thử bằng tình huống thực tế.
- Phải đo baseline thật và hỏi thêm người ngoài nhóm thay vì dùng số phút ước lượng hoặc sự đồng tình nội bộ để kết luận. AI chỉ đề xuất, còn người dùng tự xác nhận và thực hiện các hành động liên quan tới tiền.
