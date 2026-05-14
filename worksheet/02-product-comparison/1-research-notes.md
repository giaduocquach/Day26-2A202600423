---
artifact: 1 — Ghi chú nghiên cứu khi test 2 sản phẩm AI
bai-tap: 2 — Phân tích 2 sản phẩm AI (nhóm 2 học viên)
phase: Phase 2 — Thử nghiệm + chụp ảnh + research (20 phút)
time: 20 phút (xem deck Day 26 slide 18-19 để biết khung giờ chính xác)
input: group-members.md (nhóm đã chốt ngành + 2 sản phẩm + nhiệm vụ chung)
nop-cuoi: Không — file trung gian (đầu vào cho `2-comparison-table.md`)
---

# 1 — Ghi chú nghiên cứu khi test 2 sản phẩm AI

Mục tiêu: trong 20 phút thử nghiệm, 2 thành viên cùng test 2 sản phẩm AI với 1 nhiệm vụ chung. File này ghi lại **quan sát thật** (không phải đánh giá tổng kết) — sẽ làm nền cho bảng so sánh ở bước 2.

Lý do làm bước này: slide deck Lab 2 chỉ có sức nặng khi mỗi nhận định dựa trên quan sát cụ thể có ảnh chụp + tên model + thời gian + câu prompt cụ thể. Nếu chỉ "thấy A tốt hơn B" mà không có log → không phòng thủ được khi giảng viên cold-call.

Quy tắc: **không có ảnh chụp / log = không có quan sát**. Mỗi quan sát phải có ảnh tham chiếu hoặc log cụ thể (timestamp, prompt, response excerpt).

## Quy trình 20 phút

```text
2 phút   — Ghi setup chung (nhiệm vụ + câu prompt + tài khoản dùng)
8 phút   — Test Sản phẩm A: chụp 3-5 ảnh + ghi log
8 phút   — Test Sản phẩm B: chụp 3-5 ảnh + ghi log
2 phút   — First impressions: ghi 3 quan sát nổi nhất cho mỗi sản phẩm
```

---

## Phần A — Setup chung (2 phút)

Trước khi test, 2 thành viên thống nhất các thông số chung. Câu prompt phải **giống y nhau** cho cả 2 sản phẩm — nếu khác sẽ không so sánh được.

- **Nhiệm vụ chung** (1 câu mô tả): Tra cứu tỷ lệ thất nghiệp của sinh viên IT mới ra trường ở Việt Nam năm 2024 và đánh giá nguồn tin cậy.
- **Câu prompt chính xác** (paste y nguyên ở đây — sẽ dán giống vào cả 2 sản phẩm): "Tỷ lệ thất nghiệp của sinh viên IT mới ra trường ở Việt Nam năm 2024 là bao nhiêu? Nguồn nào đáng tin nhất?"
- **Loại tài khoản dùng**:
  - Sản phẩm A: Gói Free (Không cần đăng nhập)
  - Sản phẩm B: Gói Free (Không cần đăng nhập, dùng GPT-5.5 Instant)
- **Trình duyệt + thời gian test** (để dễ tham chiếu ảnh sau này): Chrome, 2026-05-14

---

## Phần B — Log Sản phẩm A (8 phút)

**Tên sản phẩm A**: Perplexity AI
**URL**: https://www.perplexity.ai
**Model dưới mui xe** (nếu hiển thị): Mặc định (Default AI)

### B.1 — Entry point + lần chạm đầu

Trước khi bắt đầu nhiệm vụ, người dùng thấy gì?

- Trang đầu / màn hình đầu hiển thị gì? Giao diện cực kỳ tối giản, logo và hộp chat lớn ở trung tâm.
- Có hint / sample prompt sẵn không? Có vài nút gợi ý chủ đề bên dưới.
- Cần đăng nhập / paywall trước khi dùng không? Không bắt buộc, dùng ngay lập tức.
- Ảnh đã chụp: `screenshots/perplexity-1-entry.jpeg`

### B.2 — Khi gõ prompt + nhận output

- Thời gian phản hồi: ~5-10 giây
- Có hiển thị "AI đang nghĩ..." / streaming hay đứng yên? Có hiển thị trạng thái đang search real-time.
- Output dài bao nhiêu (số câu / dòng / từ)? Khoảng 10-15 câu, cấu trúc tốt.
- Output có dẫn nguồn không? CÓ, rất rõ ràng (inline citations [1][2] và panel Sources ở trên cùng).
- Có hiển thị disclaimer / cảnh báo không (vd: "có thể sai", "kiểm tra lại")? Có cảnh báo số liệu thống kê có thể thay đổi tùy nguồn.
- Ảnh đã chụp: `screenshots/perplexity-2-input.jpeg` + `screenshots/perplexity-3-output.jpeg`

### B.3 — Phản hồi sau khi nhận output

- Có nút "regenerate" / "thử lại" không? Có (Rewrite).
- Có nút copy / export ra format khác không? Có nút Share, Copy.
- Có gợi ý câu hỏi tiếp theo không? Có phần Related Questions tự sinh.
- Có lưu lịch sử để truy lại không? Phải đăng nhập mới lưu.
- Có thumb up / thumb down để feedback không? Có.

### B.4 — Quan sát nổi (3 quan sát)

Ghi 3 quan sát ấn tượng nhất khi dùng. Mỗi quan sát kèm tham chiếu (ảnh hoặc log):

1. Dẫn nguồn cực kỳ rõ ràng, mỗi luận điểm đều có trích dẫn ngoặc vuông clickable liên kết trực tiếp tới website (Tham chiếu: `screenshots/perplexity-3-output.jpeg`).
2. Tốc độ tìm kiếm web nhanh, lấy dữ liệu thời gian thực mà không yêu cầu đăng nhập, giảm tối đa friction (Tham chiếu: `screenshots/perplexity-1-entry.jpeg` và `perplexity-3-output.jpeg`).
3. Đề xuất câu hỏi tiếp theo (Related Questions) rất sát với ngữ cảnh, kích thích người dùng đào sâu thêm (Tham chiếu: `screenshots/perplexity-6-related.jpeg`).

---

## Phần C — Log Sản phẩm B (8 phút)

**Tên sản phẩm B**: ChatGPT Search
**URL**: https://chatgpt.com
**Model dưới mui xe** (nếu hiển thị): GPT-5.5 Instant

### C.1 — Entry point + lần chạm đầu

- Trang đầu / màn hình đầu hiển thị gì? Hộp chat quen thuộc ở trung tâm.
- Có hint / sample prompt sẵn không? Có vài prompt gợi ý chức năng.
- Cần đăng nhập / paywall trước khi dùng không? Không bắt buộc, dùng ngay lập tức.
- Ảnh đã chụp: `screenshots/chatgpt-1-entry.jpeg`

### C.2 — Khi gõ prompt + nhận output

- Thời gian phản hồi: ~10-20 giây
- Có hiển thị "AI đang nghĩ..." / streaming hay đứng yên? Hiển thị "Searching the web...", sau đó sinh chữ (streaming).
- Output dài bao nhiêu (số câu / dòng / từ)? Khoảng 15-20 câu, dạng đoạn văn.
- Output có dẫn nguồn không? Có, nhưng đôi khi ẩn hoặc dạng text (không nhất quán).
- Có hiển thị disclaimer / cảnh báo không? Có thừa nhận khi không chắc chắn.
- Ảnh đã chụp: `screenshots/chatgpt-2-input.jpeg` + `screenshots/chatgpt-3-output.jpeg`

### C.3 — Phản hồi sau khi nhận output

- Có nút "regenerate" / "thử lại" không? Có (Regenerate).
- Có nút copy / export ra format khác không? Có nút copy.
- Có gợi ý câu hỏi tiếp theo không? Không thường xuyên hiển thị rõ như Perplexity.
- Có lưu lịch sử để truy lại không? Phải đăng nhập mới lưu.
- Có thumb up / thumb down để feedback không? Có.

### C.4 — Quan sát nổi (3 quan sát)

1. Không bắt buộc đăng nhập để sử dụng tính năng cơ bản, giảm barrier đáng kể cho người mới (Tham chiếu: `screenshots/chatgpt-1-entry.jpeg`).
2. Cách trình bày dạng trò chuyện, diễn giải số liệu sâu sắc hơn nhưng yếu trong việc trích dẫn nguồn rõ ràng (Tham chiếu: `screenshots/chatgpt-3-output.jpeg`).
3. AI tự quyết định có search web hay không, đôi khi dẫn đến câu trả lời thiếu tính real-time (Tham chiếu: `screenshots/chatgpt-3-output.jpeg`).

---

## Phần D — First impressions (2 phút)

Sau khi test cả 2, mỗi thành viên trả lời nhanh 3 câu:

1. **Sản phẩm nào "cảm giác" dễ dùng hơn lần đầu? Tại sao?**
   - ChatGPT mang lại cảm giác thân thiện hơn vì giao diện trò chuyện quen thuộc, trong khi Perplexity chuyên biệt cho tra cứu nên hơi cứng nhắc với người chỉ muốn chat.

2. **Sản phẩm nào "cảm giác" cho output đáng tin hơn? Tại sao?**
   - Perplexity đáng tin hơn hẳn vì LUÔN CÓ nguồn inline rõ ràng ở mỗi câu, dễ verify. ChatGPT đôi khi giấu nguồn hoặc chỉ tổng hợp chung chung.

3. **Câu hỏi mà nhóm CHƯA trả lời được sau 20 phút test** (sẽ cần đào thêm khi dựng slide):
   - Liệu bản nâng cấp trả phí của ChatGPT (Plus) có cải thiện luồng citation bằng tính năng search nâng cao để sánh ngang Perplexity Pro không?

> Đây là first impressions — chưa phải nhận định. Khi sang `2-comparison-table.md` sẽ đối chiếu chéo với số liệu cụ thể.

---

## Bảng kiểm trước khi sang Bước 2

- [ ] Câu prompt giống y nhau cho cả 2 sản phẩm.
- [ ] Đã chụp tối thiểu 3 ảnh cho mỗi sản phẩm (entry + input + output).
- [ ] Mỗi quan sát có ảnh / log tham chiếu.
- [ ] First impressions ghi rõ — không dùng từ chung chung như "hay hơn", "tốt hơn" mà không kèm lý do.
- [ ] Đã trả lời 5 câu trong `group-members.md` về phân chia trách nhiệm.

Sang `2-comparison-table.md` để dựng bảng so sánh 2 sản phẩm theo 5 mục của slide deck.
