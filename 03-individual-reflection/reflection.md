# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Minh Quyền
- Mã học viên: 2A202602438
- Nhóm:A1- nhom 1
- Candidate problem nhóm chọn: Sinh viên mới tốt nghiệp mất nhiều thời gian tổng hợp vị trí việc làm từ nhiều nguồn, loại bỏ tin tuyển dụng trùng lặp, tìm thêm trên trang tuyển dụng chính thức của doanh nghiệp và đánh giá mức độ phù hợp trước khi tạo danh sách rút gọn để ứng tuyển.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng |
|---|---|---|
| Scan cá nhân | Tôi lập 5 problem từ trải nghiệm học tập và làm project, trong đó có việc đọc email/tin nhắn, lập lịch và theo dõi task nhóm. | Nhóm có thêm các candidate có actor, workflow và thời gian ban đầu; top 3 của tôi đều có thể vẽ thành workflow. |
| Pitch Problem Card | Tôi pitch Card #1 về việc lọc email/tin nhắn, nêu bottleneck đọc và lọc thủ công 15–30 phút/ngày cùng rủi ro bỏ sót thông tin. | Nhóm thấy đây là pain phổ biến, đồng thời ghi nhận cần kiểm chứng số lượng tin và độ chính xác trước khi chọn giải pháp. |
| Challenge bài của bạn khác | Tôi tập trung vào các điểm chưa chắc của candidate tìm việc: tần suất tìm việc, tỷ lệ tin trùng, chất lượng đánh giá phù hợp và giới hạn thu thập dữ liệu. | Nhóm ghi nhận mốc 60–90 phút chỉ là số liệu ban đầu, cần nhật ký thử nghiệm và dữ liệu gắn nhãn trước khi kết luận. |
| Gom trùng / cluster | Tôi góp phần nhận ra các bài về tiến độ nhóm, hỏi lại task và tổng hợp ý kiến đều có root cause là thông tin bị phân tán; bài tìm việc nằm trong cluster ứng tuyển. | Nhóm rút 15 candidate về 4 cluster, tránh chọn nhiều biến thể của cùng một vấn đề. |
| Chọn candidate problem | Tôi so sánh candidate tìm việc với bài báo cáo bug và tìm tài liệu trong chat theo actor, workflow, impact và khả năng so sánh Rule/Workflow/Agent. | Candidate #7 được chọn vì có workflow rõ, impact lớn và phù hợp để thử nghiệm nhỏ. |
| Validation / research | Với vai trò research, tôi tham gia tổng hợp dữ liệu Handshake, iHire, Huntr và nghiên cứu các công cụ Teal, Huntr, Simplify cùng chính sách LinkedIn. | Nhóm có bằng chứng về hành vi tìm việc đa nguồn, nhận ra công cụ hiện có mới giải quyết từng phần, và loại tự động scrape nguồn bị cấm khỏi phạm vi. |
| Workflow nhóm | Tôi góp ý tập trung vào bước 5–6: loại tin gần trùng và đọc JD để đánh giá phù hợp, thay vì tự động hóa toàn bộ việc tìm việc. | Workflow tương lai dùng Rule cho phần rõ ràng, AI cho trích xuất/so sánh, người dùng review; có fallback khi AI không chắc. |
| Problem Statement | Tôi góp ý theo phần research rằng nguồn công khai chỉ xác nhận xu hướng tìm việc đa kênh; mốc 60–90 phút và tỷ lệ tin trùng vẫn phải đo lại. | PS v1 giữ actor là sinh viên mới tốt nghiệp, đặt metric precision/recall từ 90%, tỷ lệ chấp nhận 80% và boundary không tự nộp hồ sơ. |
| Rule / Workflow / Agent | Tôi dựa trên phần research để phân biệt công cụ theo phạm vi: Rule xử lý dữ liệu rõ ràng, AI hỗ trợ đọc/đối chiếu, còn Agent tự duyệt website có rủi ro quyền truy cập và điều khoản. | Nhóm chọn Workflow bán tự động, giữ AI ở điểm can thiệp có kiểm soát và cho phép quay về bảng Rule. |
| Decision | Tôi đồng ý với quyết định Go ở mức thử nghiệm nhỏ, không triển khai Agent; các số cần đo là thời gian trung vị, precision/recall phát hiện tin trùng và tỷ lệ tin được giữ. | Quyết định cuối có điều kiện rollback rõ: quay về bảng theo dõi và Rule nếu chất lượng hoặc thời gian không đạt. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Tôi để lại dấu tay rõ nhất ở phần research và boundary của artifact cuối: nhóm chỉ dùng link/nội dung người dùng cung cấp hoặc nguồn/API được phép, không tự động thu thập từ LinkedIn hay tự nộp hồ sơ. Phần research cũng giúp nhóm nhận ra các công cụ hiện có chỉ giải quyết từng bước, từ đó chọn Workflow có Rule, AI hỗ trợ và người dùng kiểm tra cuối.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý thêm problem theo các lăng kính sau khi tôi đã tự scan. | Giúp mở rộng góc nhìn sang các pain như tìm tài liệu và theo dõi task. | Gợi ý thường rộng, dễ trượt thành ý tưởng “trợ lý AI” thay vì pain có bằng chứng. | Tôi chỉ giữ 5 problem có actor và dấu hiệu thời gian/tần suất; tự viết lại theo trải nghiệm thật. |
| Problem Card | Phản biện bottleneck, metric và rủi ro bỏ sót của các card. | Giúp nhìn rõ card email cần human review và fallback. | AI không thể tự biết số lượng email, tỷ lệ tin quan trọng hay độ chính xác thực tế của tôi. | Tôi giữ mốc 15–30 phút là quan sát ban đầu và ghi rõ các số liệu cần đo lại. |
| Workflow | Gợi ý cách tách bước Rule, AI và người dùng trong workflow trước/sau. | Giúp kiểm tra đủ input, output, human boundary và fallback. | AI dễ đề xuất tự động hóa quá nhiều, bỏ qua thao tác nhập link và kiểm tra kết quả. | Tôi giới hạn tối đa ba loại nguồn được phép, giữ bước review bắt buộc và cho phép bỏ qua kết quả AI. |
| Research | Hỗ trợ tìm và tóm tắt các nguồn về hành vi tìm việc và công cụ hiện có. | Giúp nhóm nhanh chóng lập danh sách nguồn để kiểm tra chéo. | Tóm tắt AI có thể làm số liệu hoặc phạm vi nghiên cứu nghe chắc chắn hơn thực tế. | Tôi chỉ dùng link kiểm được, ghi rõ cỡ mẫu không nêu ngay trên trang và không dùng nguồn để chứng minh tỷ lệ tin trùng. |
| Problem Statement | Phản biện field còn mơ hồ như “phù hợp”, baseline và boundary. | Giúp phát hiện cần đo cả tốc độ lẫn precision/recall, tỷ lệ chấp nhận. | AI không thể tự quyết định metric nào phù hợp với trách nhiệm của người tìm việc. | Tôi cùng nhóm định nghĩa đầu vào, nhóm nguồn, mục tiêu thử nghiệm và loại việc tự động scrape/nộp hồ sơ. |
| Rule / Workflow / Agent | So sánh khả năng của Rule, Workflow và Agent cho candidate. | Giúp làm rõ Rule đủ cho trùng rõ ràng nhưng chưa đủ cho ngữ nghĩa JD. | AI có xu hướng xem Agent là lựa chọn tiện lợi dù quyền truy cập và hậu quả sai chưa chấp nhận được. | Tôi ủng hộ Workflow, dùng AI như bộ gợi ý có dẫn chứng và giữ người dùng duyệt mọi quyết định. |
| Decision | Hỏi ngược về điều kiện Go, dữ liệu thử nghiệm và rollback. | Giúp nhóm biến quyết định thành một thử nghiệm có chỉ số và ngưỡng dừng. | AI không thay được đánh giá của nhóm về tính khả thi của dữ liệu và điều khoản website. | Tôi giữ quyết định “Go thử nghiệm nhỏ”, đồng thời yêu cầu đo lại baseline trước khi mở rộng. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Khi nghe top 3 problems của các bạn, tôi học được rằng một problem hấp dẫn chưa chắc là problem nên chọn: phải nhìn cả actor, workflow, bằng chứng và khả năng làm trong lab. Nhóm từng có nguy cơ solution-first vì candidate tìm việc nghe rất hợp để làm một Agent tự quét nhiều website. Sau khi xem công cụ hiện có và chính sách LinkedIn, tôi thay đổi cách nhìn: phần khó không phải cứ tự động hóa càng nhiều càng tốt mà là kiểm soát nguồn dữ liệu và lỗi gộp nhầm tin. Tôi cũng nhận ra từ “phù hợp” rất dễ trở thành đánh giá chủ quan nếu không gắn với tiêu chí bắt buộc, tiêu chí ưu tiên và hồ sơ của người dùng. Dấu tay của tôi trong artifact cuối rõ nhất ở phần research và boundary của Workflow bán tự động. Tôi góp phần đưa các nguồn công khai vào đúng vai trò củng cố xu hướng, không dùng chúng để khẳng định mốc 60–90 phút hay tỷ lệ tin trùng của mọi sinh viên. Điều khó nhất khi viết Problem Statement là tách số liệu ban đầu khỏi metric mục tiêu và chỉ ra cách đo để không hứa quá mức. Nếu làm lại, tôi sẽ challenge nhóm sớm hơn về cách gắn nhãn 50–100 tin và cách đo precision/recall trước khi chốt mục tiêu 90%. Qua bài này, tôi hiểu quyết định Go tốt không nhất thiết là triển khai sản phẩm hoàn chỉnh mà có thể là một thử nghiệm nhỏ, có người kiểm tra và điều kiện quay về cách cũ.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

