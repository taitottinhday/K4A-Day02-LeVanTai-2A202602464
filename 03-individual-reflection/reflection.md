# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Lê Văn Tài
- Mã học viên: 2A202602464
- Nhóm: Thân-Tý-Dậu
- Candidate problem nhóm chọn: Chuẩn bị checklist lab từ đúng nguồn và đúng phiên bản.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tôi scan 10 vấn đề từ trải nghiệm học, làm lab và phối hợp nhóm; sau đó chọn ba vấn đề về tìm đúng tài liệu, tổng hợp deadline và đọc tài liệu kỹ thuật. | Ba Problem Cards của tôi trở thành candidate #10–#12 trong bảng hội tụ; hai candidate đầu góp trực tiếp vào cluster A và candidate còn lại thuộc cluster B. |
| Pitch Problem Card | Tôi trình bày bài toán tìm đúng tài liệu và phiên bản bài làm, gồm actor, workflow năm bước, điểm nghẽn ở khâu tìm/so sánh tệp và các metric có thể đo. | Nhóm nhận ra bài toán của tôi trùng mạnh với pain hiểu yêu cầu lab, tổng hợp deadline và kiểm tra bài nộp của nhiều thành viên khác. |
| Challenge bài của bạn khác | Tôi đặt câu hỏi liệu checklist, cấu trúc thư mục và Rule-only đã giải quyết được phần lớn vấn đề hay chưa; đồng thời yêu cầu làm rõ source of truth khi các nguồn mâu thuẫn. | Câu hỏi giúp nhóm không mặc định phải xây Agent và đưa phương án checklist/Rule-only vào baseline đối chứng. |
| Gom trùng / cluster | Tôi đối chiếu ba candidate của mình với các ý #4, #13–#15 và #19; hai vấn đề đầu được gom vào cluster A, còn vấn đề đọc tài liệu được gom vào cluster B. | Cluster A trở thành cụm mạnh nhất với bảy candidate liên quan đến yêu cầu, phiên bản, deadline và bài nộp lab. |
| Chọn candidate problem | Tôi ủng hộ candidate “Chuẩn bị checklist lab từ đúng nguồn và đúng phiên bản” vì sát bối cảnh của cả nhóm, đầu vào sẵn có và output có thể kiểm đúng/sai. | Candidate này đạt 34 điểm, cao nhất trong ba phương án shortlist, và được chọn để đào sâu. |
| Validation / research | Tôi cung cấp ba Problem Cards làm một phần dữ liệu cho mini-poll nội bộ, đồng thời phân biệt số liệu ước tính cá nhân với bằng chứng đã được đo. Tôi cùng nhóm đối chiếu các pattern như GitHub Copilot Spaces, Discord Search và Gemini Notebook. | Nhóm thu hẹp pain từ “AI giúp chuẩn bị lab” thành “tạo checklist có dẫn nguồn” và không trình bày baseline sơ bộ như số liệu đã được kiểm chứng. |
| Workflow nhóm | Tôi đóng góp các bước tìm đúng phiên bản, tổng hợp yêu cầu/deadline, map nguồn thành checklist và bắt buộc người học xác minh trước khi sử dụng. | Workflow tương lai tách rõ việc của Rule, AI và con người; bổ sung trạng thái `UNRESOLVED` khi thiếu nguồn hoặc có mâu thuẫn. |
| Problem Statement | Tôi góp phần làm rõ actor là sinh viên làm lab, bottleneck là map nhiều nguồn thành checklist, cùng các metric về thời gian, deliverable và khả năng truy vết. | Problem Statement v1 có output cụ thể, success metric đo trên ba lab và boundary không giải hộ, không tự chọn nguồn, không tự nộp bài. |
| Rule / Workflow / Agent | Tôi đề xuất Rule xử lý metadata, định dạng checklist và kiểm cấu trúc; AI chỉ trích xuất yêu cầu tự nhiên có dẫn nguồn; sinh viên review kết quả. | Nhóm chọn Workflow, không chọn Agent vì luồng chính đã biết trước và AI không được quyền quyết định source of truth. |
| Decision | Tôi ủng hộ “Go với pilot nhỏ; Not Yet cho tích hợp tự động hoặc Agent”, đồng thời giữ Rule-only làm phương án đối chứng. | Nhóm xây dựng pilot trên ba lab và xác định điều kiện tiếp tục, dừng hoặc rollback dựa trên thời gian, lỗi bỏ sót và tỷ lệ nội dung phải sửa. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Ba Problem Cards của tôi giúp nhóm nhận ra mối liên hệ giữa việc tìm đúng tài liệu,
tổng hợp deadline và tạo checklist trước lab. Dấu tay rõ nhất của tôi là yêu cầu tách
Rule, AI và human review, đồng thời không để hệ thống tự chọn source of truth.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Tôi dùng AI để phản biện và chuẩn hóa cách diễn đạt sau khi tự liệt kê vấn đề. | AI giúp nhìn thêm các góc quản lý phiên bản, checklist và feedback. | AI có xu hướng gợi ý các bài toán quá rộng và không có bằng chứng thật. | Tôi chỉ giữ pain đã gặp, ghi số liệu chưa đo là baseline ước tính và nêu cách kiểm chứng. |
| Problem Card | Tôi dùng AI để kiểm tra actor, workflow, bottleneck, impact và metric của ba Card. | AI giúp các Card có cùng cấu trúc và chỉ ra trường còn mơ hồ. | Gợi ý ban đầu thiên về giải pháp như semantic search hoặc trợ lý AI trước khi chứng minh process fix chưa đủ. | Tôi đặt chuẩn hóa thư mục/checklist làm phương án đầu tiên và thu hẹp AI vào một bước cụ thể. |
| Workflow | Tôi dùng AI để phản biện workflow trước/sau, phân vai Rule–AI–người và đề xuất fallback. | AI giúp làm rõ handoff, human boundary và bước dễ tự động hóa. | Thời gian sau cải tiến do AI đề xuất còn lạc quan vì chưa có log thực tế. | Tôi giữ con số là mục tiêu pilot, bổ sung bấm giờ trên ba lab và điều kiện rollback. |
| Research | Tôi dùng AI để hệ thống hóa cách các công cụ đã chọn giải quyết tìm kiếm, grounded context và tóm tắt theo nguồn. | AI giúp so sánh nhanh điểm mạnh, khoảng trống và bài học cho nhóm. | Bản tóm tắt có thể bỏ qua giới hạn sản phẩm hoặc biến nhận định thành bằng chứng. | Tôi chỉ dùng thông tin kiểm tra được qua link chính thức và không dùng AI làm source of truth. |
| Problem Statement | Tôi dùng AI để phản biện v0 và tìm các từ chưa đo được như “chuẩn bị”, “đáng tin cậy” hoặc “không bỏ sót”. | AI giúp chuyển mô tả rộng thành các field và metric cụ thể. | AI chưa tự biết nguồn nào là chính thức và không thể xác nhận baseline của nhóm. | Tôi bổ sung nguồn do sinh viên xác nhận, output checklist có citation và cách đo trên ba lab. |
| Rule / Workflow / Agent | Tôi dùng AI để so sánh mức tự chủ, rủi ro và phạm vi phù hợp của ba phương án. | AI giúp làm rõ Rule xử lý phần đúng/sai, còn AI chỉ hỗ trợ hiểu ngôn ngữ tự nhiên. | AI có thể đề xuất Agent phức tạp hơn nhu cầu và xem nhẹ quyền truy cập dữ liệu. | Tôi chọn Workflow có human review, loại Agent và giữ Rule-only làm baseline. |
| Decision | Tôi dùng AI để challenge điều kiện Go/Not Yet/No-Go và đề xuất tiêu chí dừng. | AI giúp nhóm viết pilot, metric và rollback rõ ràng. | AI không thể quyết định hiệu quả khi baseline chưa được đo đồng nhất. | Tôi chỉ ủng hộ Go có điều kiện cho pilot; chưa tích hợp tự động cho đến khi có bằng chứng. |

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
Khi nghe 21 candidate problems của các thành viên, tôi nhận ra nhiều vấn đề khác nhau
thực chất cùng xuất phát từ việc thông tin quan trọng nằm rải rác và chưa có source of truth.
Sau khi bị challenge, tôi thay đổi từ hướng nghĩ về một công cụ AI tổng quát sang một
workflow nhỏ, trong đó từng bước đều có đầu vào, đầu ra và người chịu trách nhiệm rõ ràng.
Ban đầu tôi xem việc tìm tài liệu, theo dõi deadline và đọc tài liệu kỹ thuật là ba bài toán
tách biệt, nhưng quá trình gom cluster cho thấy hai bài đầu có thể hội tụ vào workflow tạo
checklist trước lab. Đóng góp rõ nhất của tôi là ba Problem Cards #10–#12 và câu hỏi liệu
Rule/checklist đơn giản có giải quyết đủ trước khi đưa AI vào hay không. Phần khó nhất khi
viết Problem Statement là xác định metric, vì baseline 30–45 phút mới chỉ là số liệu sơ bộ
và chưa được bấm giờ đồng nhất trên cả nhóm. Tôi cũng hiểu rằng boundary rất quan trọng:
hệ thống chỉ tạo draft có dẫn nguồn, còn sinh viên phải xác minh và chịu trách nhiệm cuối.
AI hữu ích khi cấu trúc hóa lập luận, nhưng các ước tính do AI gợi ý không thể thay cho
log thời gian, phỏng vấn và kết quả thử nghiệm thực tế của nhóm.
Việc so sánh Rule, Workflow và Agent giúp nhóm tránh solution-first và chọn Workflow vừa
đủ thay vì một Agent có quyền quá rộng. Nếu làm lại, tôi sẽ đo ba lab ngay từ đầu, phỏng
vấn thêm 2–3 học viên ngoài nhóm và challenge mạnh hơn bằng kết quả A/B với Rule-only.
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
