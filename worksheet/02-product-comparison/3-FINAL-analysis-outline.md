---
artifact: 3 — Outline 5 mục cho slide deck Analysis Report
bai-tap: 2 — Phân tích 2 sản phẩm AI (nhóm 2 học viên)
phase: Phase 3 — Dựng slide deck (15 phút)
time: 10 phút outline + 5 phút build slide
input: 1-research-notes.md + 2-comparison-table.md + screenshots/ + prompts/08-analysis-report.md
nop-cuoi: Có gián tiếp — outline này dùng làm cốt cho `analysis-report.pdf` (deliverable bắt buộc)
---

# 3 — Outline 5 mục cho slide deck (S1 → S5 với S5 mở rộng 8 sub-mục)

Mục tiêu: dựng outline đầy đủ cho slide deck Analysis Report ngay trong file markdown — viết hết nội dung 5 mục ở đây trước, sau đó copy sang slide (pptx / Keynote / Google Slides). Không build slide trước khi outline xong.

Lý do làm bước này: dựng thẳng slide từ log dễ bị thiếu mục hoặc bị "đẹp ngoài rỗng trong". Outline markdown ép nhóm trả lời từng câu hỏi trước khi nghĩ về thiết kế slide. Khi giảng viên / nhóm khác hỏi "vì sao bạn xếp Sản phẩm A là Promising?" — câu trả lời đã có sẵn trong outline.

Quy tắc: mỗi nhận định trong outline phải nối được về bằng chứng cụ thể (ảnh / log / số liệu công khai). Nếu một sub-mục để trống → quay lại `1-research-notes.md` đào thêm trước khi sang slide.

## Quy trình 15 phút

```text
2 phút  — Đọc lại 2-comparison-table.md để có context
8 phút  — Điền outline 5 mục (S1 → S5)
4 phút  — Riêng cho S5: mở rộng 8 sub-mục (S5.1 → S5.8)
1 phút  — Đối chiếu bảng kiểm trước khi build slide
```

> Sau 15 phút outline + đối chiếu, mới mở pptx / Google Slides / Keynote và copy nội dung sang. Slide deck export thành `analysis-report.pdf` ở cùng folder này.

---

## Thông tin chung của báo cáo

- **Mã 2 thành viên + tên**: 2A202600423 (Quách Gia Được) + 2A202600205 (Nguyễn Thành Nam)
- **Ngành chọn**: A — Tìm kiếm
- **Nhiệm vụ chung đã test**: Tra cứu tỷ lệ thất nghiệp của sinh viên IT mới ra trường ở Việt Nam năm 2024 và đánh giá nguồn tin cậy.
- **Sản phẩm A** (tên + URL): Perplexity AI (https://www.perplexity.ai)
- **Sản phẩm B** (tên + URL): ChatGPT Search (https://chatgpt.com)
- **Câu prompt chính xác đã dùng**: "Tỷ lệ thất nghiệp của sinh viên IT mới ra trường ở Việt Nam năm 2024 là bao nhiêu? Nguồn nào đáng tin nhất?"

---

## S1 — Product Moment (slide 1-2)

Mục đích: định danh rõ 2 sản phẩm, nhiệm vụ chung, điểm gặp đầu (entry point).

### S1.1 — Bảng so sánh nhanh

| Yếu tố | Sản phẩm A | Sản phẩm B |
|---|---|---|
| Tên + URL | Perplexity AI | ChatGPT Search |
| Entry point (trang đầu nhìn thấy gì) | Hộp chat lớn, tập trung vào tìm kiếm | Hộp chat quen thuộc, đa chức năng |
| Ý định người dùng (vào để làm gì) | "Tìm thông tin có nguồn rõ ràng" | "Trò chuyện, hỏi đáp đa năng" |
| Surface chính (chat / form / canvas / IDE / khác) | Chat / Search Interface | Chat |
| Có cần đăng nhập / paywall ngay không | Không | Không |

### S1.2 — Bằng chứng (ảnh tham chiếu)

- `screenshots/perplexity-1-entry.jpeg` — Hộp chat tối giản, có chữ "Ask anything" tập trung hoàn toàn vào việc nhận query.
- `screenshots/chatgpt-1-entry.jpeg` — Hộp chat với các gợi ý chức năng (Create image, Analyze data) cho thấy tính đa năng.

### S1.3 — Nhận định so sánh entry point (2-3 câu)

Cả hai sản phẩm đều sở hữu entry point vô cùng tối giản và loại bỏ rào cản đăng nhập ban đầu, giúp người dùng trải nghiệm "aha moment" ngay lập tức. Tuy nhiên, Perplexity định vị rất rõ là công cụ "Answer Engine" chuyên biệt cho tra cứu, trong khi ChatGPT đóng vai trò là "AI Assistant" đa năng.

---

## S2 — Workflow Evidence (slide 3-4)

Mục đích: hiển thị luồng người dùng + 3 friction areas (Lens 3).

### S2.1 — Luồng người dùng (trước / trong / sau khi dùng AI)

```text
TRƯỚC khi gặp AI:
- Người dùng đang cần tìm số liệu thất nghiệp ngành IT để làm báo cáo, mở trình duyệt.

TRONG khi dùng Sản phẩm A (Perplexity):
1. Gõ prompt và nhấn Enter.
2. AI lập tức search web (có hiển thị thanh tiến trình và các nguồn đang đọc).
3. AI sinh văn bản, đính kèm số [1], [2] tương ứng với nguồn ở đầu trang.

TRONG khi dùng Sản phẩm B (ChatGPT):
1. Gõ prompt và nhấn Enter.
2. AI tự quyết định có trigger module "Search" hay không.
3. AI sinh văn bản đoạn văn, thỉnh thoảng có biểu tượng ngoặc kép nhỏ cuối câu.

SAU khi dùng AI:
- Người dùng click thẳng vào link để kiểm chứng số liệu gốc trước khi copy vào báo cáo.
```

### S2.2 — 3 Friction Areas (Lens 3)

| Friction | Sản phẩm A | Sản phẩm B |
|---|---|---|
| **Physical load** (số click, tab, copy-paste) | Rất thấp (1 click để mở bài báo gốc). | Cao hơn (nếu nguồn ẩn, phải tự mở tab search Google để double check). |
| **Cognitive burden** (cần học prompt eng. / nhớ ngữ cảnh giữa lượt chat) | Thấp (hoàn toàn an tâm về tính xác thực nhờ citations). | Cao (phải liên tục tự hỏi "số liệu này AI lấy ở đâu ra, có thật không?"). |
| **User workarounds** (nhóm phải tự làm gì để bù yếu điểm) | Không cần thiết. | Thường xuyên phải thêm câu "Hãy tìm kiếm trên web và trích dẫn URL rõ ràng". |

### S2.3 — Bằng chứng

- `screenshots/perplexity-2-input.jpeg` + `screenshots/perplexity-3-output.jpeg`
- `screenshots/chatgpt-2-input.jpeg` + `screenshots/chatgpt-3-output.jpeg`

### S2.4 — Nhận định: sản phẩm nào giảm friction tốt hơn? Tại sao? (3-4 câu)

Perplexity giảm friction tốt hơn vượt trội khi xét đến tác vụ "tra cứu cần kiểm chứng". Bằng cách đưa citations lên hàng đầu (front and center), nó loại bỏ hoàn toàn "cognitive burden" về nỗi lo AI hallucination. ChatGPT hướng đến trải nghiệm trò chuyện mượt mà nên đôi khi giấu đi các bước search trung gian, vô tình làm tăng physical load khi người dùng cần verify số liệu.

---

## S3 — Output & Trust (slide 5-6)

Mục đích: đánh giá chất lượng output + 6 tín hiệu đáng tin.

### S3.1 — Chất lượng output

Cho mỗi sản phẩm, trả lời 3 câu:

- **Sản phẩm A**:
  - Output có **trả lời đúng câu hỏi** chính không? Có, lấy đúng số liệu 2024.
  - Output có **bịa thông tin** không (hallucination)? Nếu có, chỗ nào? Không, nội dung lấy nguyên văn từ báo chí.
  - Output có **đầy đủ** hay nửa vời? Cực kỳ đầy đủ, chia thành các gạch đầu dòng rõ ràng.
- **Sản phẩm B**:
  - Output có **trả lời đúng câu hỏi** chính không? Có trả lời đúng.
  - Output có **bịa thông tin** không? Không.
  - Output có **đầy đủ** hay nửa vời? Dưới dạng phân tích, rất mạch lạc nhưng thiếu dẫn chứng tường minh.

### S3.2 — 6 Tín hiệu đáng tin (đối chiếu)

| Tín hiệu | Sản phẩm A | Sản phẩm B |
|---|---|---|
| 1. Dẫn nguồn (citation mở được, đúng nội dung) | Có (luôn có inline) | Không nhất quán (thường ẩn) |
| 2. Disclaimer khi không chắc | Có | Có |
| 3. Fallback / dừng lại khi out-of-scope | Có | Có |
| 4. Consistency (chạy 2 lần cùng prompt) | Rất cao | Trung bình |
| 5. User control (sửa, dừng, regenerate, undo) | Có | Có |
| 6. Explanation (giải thích "vì sao AI nói thế") | Qua citations cụ thể | Qua reasoning văn bản |

### S3.3 — Nhận định: sản phẩm nào tạo trust mạnh hơn? Vì sao? (3-4 câu)

Perplexity tạo ra sự tin tưởng (trust) mạnh mẽ và trực tiếp hơn hẳn. Bằng cách ưu tiên 100% hiển thị nguồn URL rõ ràng bên cạnh mỗi mệnh đề, Perplexity trao quyền kiểm soát "sự thật" lại cho người dùng. ChatGPT dù giải thích logic tốt nhưng sự mập mờ trong việc trích xuất nguồn gốc dữ liệu làm giảm đi độ đáng tin trong môi trường học thuật/công việc.

---

## S4 — Business Signal (slide 7)

Mục đích: định vị 2 sản phẩm trên Cost-Capability-Speed + pricing pattern.

### S4.1 — Định vị tam giác (cho mỗi sản phẩm)

- **Sản phẩm A**: Rẻ-nhanh — model dưới mui xe: Default AI (GPT/Claude mix) — lý do định vị 1 câu: Giải quyết trọn vẹn bài toán tra cứu số liệu với tốc độ cao (~5s) ngay trên gói Free.
- **Sản phẩm B**: Cân bằng / Đa năng — model dưới mui xe: GPT-5.5 Instant — lý do định vị 1 câu: Không chuyên biệt sâu vào search nhưng cung cấp giải pháp đủ tốt cho mọi tác vụ (code, viết, voice).

### S4.2 — Pricing pattern

| Yếu tố | Sản phẩm A | Sản phẩm B |
|---|---|---|
| Mô hình giá | Freemium ($20/tháng Pro) | Freemium ($20/tháng Plus) |
| Giá entry (free tier giới hạn gì) | Unlimited basic search, ~5 Pro search/ngày | Giới hạn tin nhắn, giới hạn DALL-E/Voice |
| Giá trả phí (gói chính + giá) | Pro $20/tháng (Deep Research, Multi-model) | Plus $20/tháng (GPT-5.5, o3, Voice) |
| Paywall xuất hiện ở đâu (khi hết quota / tính năng nâng cao / etc.) | Khi chọn đổi mô hình (Claude/GPT) hoặc hết Pro search | Khi gửi quá nhiều tin nhắn hoặc dùng Advanced Voice |

### S4.3 — Nhận định: chiến lược kinh doanh của 2 sản phẩm khác nhau thế nào? (2-3 câu)

Perplexity tập trung bán khả năng "Agentic Research" và cho người dùng quyền tự chọn nền tảng model (Claude, OpenAI) bên dưới — đóng vai trò aggregator. ChatGPT Plus tập trung bán hệ sinh thái All-in-one do chính họ phát triển với các tính năng đa phương tiện (Voice, Vision, Reasoning) làm mồi nhử.

---

## S5 — Product Judgment (slide 8-12 — phần đậm nhất)

Mục đích: ra verdict + vận dụng 4 Lens + Spark/Loop/System + Niche/Feature Map + liên hệ Lab 1.

S5 mở rộng thành 8 sub-mục — bắt buộc xong **S5.1, S5.6, S5.7, S5.8**. Nhóm khá phải hoàn thành cả 8 sub-mục. Nhóm Đạt có thể ghi "không có nguồn công khai" cho 1-2 số liệu ở S5.2-S5.5 nhưng phải ghi rõ.

### S5.1 — Verdict (BẮT BUỘC)

- **Sản phẩm A**: Strong — Lý do: Làm chủ hoàn toàn ngách AI Search với ARR tăng trưởng khủng ($450-500M) và giải quyết trọn vẹn "trust problem".
- **Sản phẩm B**: Strong — Lý do: Vị thế quá lớn (900M WAU, $25B ARR) và Data flywheel khổng lồ giúp bảo vệ sản phẩm khỏi các rủi ro ngắn hạn.

### S5.2 — User base + tăng trưởng

- **Sản phẩm A**: 100M+ MAU (Nguồn báo cáo Q1/2026)
- **Sản phẩm B**: 900M WAU, 1B+ MAU (Nguồn báo cáo 02/2026)

### S5.3 — Doanh thu / pricing power

- **Sản phẩm A**: ~$450-500M ARR (Q1/2026) + chiến lược pricing: Freemium, Enterprise ($40/seat)
- **Sản phẩm B**: ~$25B ARR (02/2026) + chiến lược pricing: Freemium, Team, Enterprise

### S5.4 — Moat phân tích (5 loại)

| Moat | Sản phẩm A | Sản phẩm B |
|---|---|---|
| Data (proprietary data flywheel) | Trung bình (Sonar Index) | Rất mạnh (2.5B prompts/ngày cho RLHF) |
| Network effects | Yếu (Single-player tool) | Trung bình (GPTs ecosystem) |
| Switching cost (chi phí đổi sang sản phẩm khác) | Yếu (Dễ dàng chuyển đổi) | Trung bình (History, Custom Instructions) |
| Brand | Trung bình (Nổi trong giới tech/research) | Rất mạnh (Brand mặc định khi nói về AI) |
| Distribution (kênh tiếp cận user) | Yếu (Chủ yếu qua word of mouth) | Rất mạnh (Microsoft, iOS integration) |

### S5.5 — Data flywheel + feedback loop

- **Sản phẩm A**: Người dùng search → Cải thiện retrieval engine (Sonar) → Cung cấp API tốt hơn cho devs → Tăng thêm queries. (Có compounding, tốc độ khá).
- **Sản phẩm B**: Hàng tỷ lượt prompts/ngày → Dữ liệu cho quá trình RLHF → Model thông minh hơn → Thu hút thêm hàng triệu người dùng mới. (Compounding cực mạnh).

### S5.6 — Niche Down + AI Feature Map (BẮT BUỘC)

- **Sản phẩm A**:
  - Niche cụ thể (đối tượng người dùng + use case): Người nghiên cứu, sinh viên, chuyên gia cần tra cứu thông tin thời gian thực CÓ nguồn.
  - AI Feature Map:
    - User Value: Cao — Xóa bỏ hoàn toàn nỗi lo AI hallucinate.
    - User Alignment: Cao — Giao diện chuyên biệt cho research.
    - Business Value: Cao — ARR tăng 2.5x trong 6 tháng.
- **Sản phẩm B**:
  - Niche cụ thể: Tất cả mọi người (All-in-one AI Assistant).
  - AI Feature Map:
    - User Value: Cao — Đa năng, làm được mọi việc từ code đến viết lách.
    - User Alignment: Cao — Dễ dùng như nhắn tin.
    - Business Value: Cao — Định giá $852B.

### S5.7 — Spark → Loop → System (BẮT BUỘC)

- **Sản phẩm A**: Loop sang System — Lý do: Đã chứng minh được product-market fit mạnh, đang cố gắng trở thành System thông qua Enterprise và Perplexity Computer (agentic) — Dự báo 12 tháng tới: Đối mặt với rủi ro bị Google bóp nghẹt.
- **Sản phẩm B**: System — Lý do: Đã trở thành một ecosystem khổng lồ chi phối thị trường — Dự báo 12 tháng tới: Tích hợp sâu hơn vào các OS (iOS/Windows) dưới dạng Agent.

### S5.8 — Liên hệ Lab 1 (BẮT BUỘC)

- Sản phẩm A có rủi ro disruption tương tự case nào của nhóm? Giống hệt Shutterstock: Nguy cơ bị Google AI Overviews "Squeeze" (chèn ép) ngay trên kênh phân phối chính. Nếu Google tích hợp AI Search đủ tốt vào trình duyệt mặc định, Perplexity sẽ mất thị phần.
- Sản phẩm B có rủi ro disruption tương tự case nào của nhóm? ChatGPT ĐANG đóng vai trò là "kẻ đi Disrupt" các hệ thống truyền thống (như Shutterstock).
- Bài học rút từ Lab 1 áp dụng được cho 2 sản phẩm này thế nào? Để không bị "squeeze", Perplexity bắt buộc phải build moat bằng Enterprise, API và các tính năng Agentic độc quyền (Perplexity Computer) mà đối thủ lớn khó copy nhanh chóng.

---

## Bảng kiểm trước khi build slide

- [ ] S1 → S4 đã điền đầy đủ.
- [ ] S5.1 + S5.6 + S5.7 + S5.8 đã hoàn thành (4 sub-mục bắt buộc).
- [ ] S5.2 → S5.5 đã hoàn thành (hoặc đã ghi rõ "không có nguồn công khai" cho ô trống).
- [ ] Mỗi nhận định nối được về ảnh / log / số liệu cụ thể.
- [ ] Verdict ở S5.1 nhất quán với phân tích moat ở S5.4 và giai đoạn ở S5.7.
- [ ] 2 thành viên cùng đồng ý với toàn bộ outline.

---

## Sau khi xong outline

1. Mở pptx / Keynote / Google Slides / Figma.
2. Tạo 12-15 slide bám theo cấu trúc S1 → S5 ở trên (mỗi mục 1-3 slide).
3. **Mỗi slide có ít nhất 1 ảnh tham chiếu** (từ `screenshots/`).
4. Export PDF → lưu thành `analysis-report.pdf` trong cùng folder này.
5. Nếu dùng Google Slides công khai, lưu link vào `analysis-report-link.md` (tuỳ chọn).
6. 2 thành viên cùng copy `analysis-report.pdf` + `group-members.md` về repo cá nhân của mình.

> Tham khảo `prompts/08-analysis-report.md` nếu cần AI hỗ trợ build slide từ outline này.
