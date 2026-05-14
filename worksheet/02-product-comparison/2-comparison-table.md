---
artifact: 2 — Bảng so sánh 2 sản phẩm theo 5 mục
bai-tap: 2 — Phân tích 2 sản phẩm AI (nhóm 2 học viên)
phase: Chuyển giao Phase 2 → Phase 3 (5 phút)
time: 5 phút
input: 1-research-notes.md + screenshots/
nop-cuoi: Không — file trung gian (đầu vào cho `3-FINAL-analysis-outline.md`)
---

# 2 — Bảng so sánh 2 sản phẩm theo 5 mục slide deck

Mục tiêu: gộp toàn bộ quan sát ở Bước 1 thành **một bảng so sánh nén** — cùng cấu trúc 5 mục mà slide deck cuối sẽ dùng. Sau bước này, nhóm có "khung xương" của slide deck.

Lý do làm bước này: nhảy thẳng từ log sang slide deck dễ bị bỏ sót mục. Bảng so sánh ép nhóm trả lời từng mục cho cả 2 sản phẩm song song — phát hiện ngay nếu mục nào còn thiếu bằng chứng.

Quy tắc: mỗi ô của bảng dài tối đa 2 câu. Nếu ô nào để trống → quay lại `1-research-notes.md` đào thêm trước khi sang Bước 3.

## Quy trình 5 phút

```text
3 phút  — Điền bảng so sánh 5 mục (5 dòng × 2 cột)
1 phút  — Đánh dấu ô nào còn thiếu bằng chứng
1 phút  — Quyết định: cần test thêm hay đủ để sang slide?
```

---

## Phần A — Bảng so sánh 5 mục

| Mục | Sản phẩm A | Sản phẩm B |
|---|---|---|
| **S1 — Product Moment**<br><sup>Entry point + ý định người dùng + surface chính (chat / form / canvas / IDE)</sup> | perplexity.ai → hộp chat. Ý định: "Tìm thông tin có nguồn". | chatgpt.com → hộp chat đa năng. Ý định: "Trò chuyện, hỏi đáp". |
| **S2 — Workflow Evidence**<br><sup>Trước / trong / sau khi dùng AI. Friction chính (số click, tab, copy-paste, load mental)</sup> | Nhập prompt → search real-time → xem inline citations → click nguồn. Friction cực thấp. | Nhập prompt → AI tự quyết định có search không → đọc text. Friction cao khi cần verify nguồn. |
| **S3 — Output &amp; Trust**<br><sup>Chất lượng output + dẫn nguồn + disclaimer + control cho người dùng</sup> | Output chuẩn cấu trúc, LUÔN CÓ nguồn inline [1][2], verify dễ dàng bằng 1 click. | Output diễn giải sâu sắc nhưng nguồn không nhất quán, đôi khi phải copy URL thủ công để check. |
| **S4 — Business Signal**<br><sup>Pricing + giới hạn / paywall + định vị Cost-Capability-Speed (rẻ-nhanh hay mạnh-đắt)</sup> | $20/tháng (Deep Research, agentic). Free: giới hạn ~5 Pro search/ngày. Định vị: Rẻ-Nhanh. | $20/tháng (Voice, o3, DALL-E). Free: giới hạn tin nhắn/giờ. Định vị: Cân bằng, Đa năng. |
| **S5 — Product Judgment**<br><sup>Verdict 1 dòng: Strong / Promising / Weak / At Risk + lý do</sup> | **Strong** — Niche AI search rất rõ ràng, ARR tăng trưởng đột phá ($450-500M). | **Strong** — Dominant platform (900M WAU, $25B ARR), quá lớn để thất bại ngắn hạn. |

---

## Phần B — Đối chiếu 3 friction areas (nén từ Lens 3)

Đây là cột trụ của mục S2 trong slide deck. Mỗi friction area trả lời 1 câu so sánh:

- **Physical load** (số click / tab / lần copy-paste): Perplexity tối ưu hơn vì nguồn có thể click trực tiếp (1 click), ChatGPT đòi hỏi thao tác copy-paste nếu nguồn ẩn.
- **Cognitive burden** (cần học prompt engineering / có hint sẵn / có nhớ ngữ cảnh giữa lượt chat):
  - ChatGPT đòi hỏi người dùng tự chịu tải trọng tâm lý (cognitive burden) cao hơn trong việc kiểm chứng xem AI có hallucinate hay không.
- **User workarounds** (nhóm phải tự làm gì để bù yếu điểm — vd: prompt lại 3 lần, copy sang công cụ khác):
  - Với ChatGPT, đôi khi phải chủ động nhắc "hãy search web và cung cấp URL" để buộc AI lấy số liệu mới nhất.

---

## Phần C — Đối chiếu 6 trust signals (nén cho mục S3)

Đánh dấu mỗi sản phẩm có / không / một phần:

| Tín hiệu đáng tin | Sản phẩm A | Sản phẩm B |
|---|---|---|
| 1. Dẫn nguồn (citation) — link mở được, đúng nội dung | ✅ Luôn có (inline clickable) | ⚠️ Có nhưng không nhất quán |
| 2. Disclaimer khi không chắc ("không tìm được", "có thể sai") | ✅ Có ghi nhận | ✅ Có thừa nhận |
| 3. Fallback / dừng lại khi out-of-scope | ✅ Có | ✅ Có |
| 4. Consistency — chạy 2 lần cùng prompt, output có giống không | ✅ Rất nhất quán | ⚠️ Có thể thay đổi cách giải thích |
| 5. User control — sửa lại, dừng, regenerate, undo | ✅ Có (Rewrite) | ✅ Có (Regenerate) |
| 6. Explanation — giải thích "tại sao AI nói thế" (nếu có) | ✅ Giải thích bằng cách trích nguồn rõ ràng | ✅ Giải thích bằng reasoning/logic sâu |

---

## Phần D — Định vị 2 sản phẩm trên Cost-Capability-Speed (cho mục S4)

Mỗi sản phẩm chọn **1** trong 3 góc tam giác (vẽ hình tay nếu cần — sẽ dán vào slide S4):

- **Sản phẩm A nghiêng về**: Rẻ-nhanh — lý do 1 câu: Đáp ứng nhu cầu tra cứu số liệu tức thì (5s) với độ tin cậy cao trên gói Free.
- **Sản phẩm B nghiêng về**: Cân bằng / Đa năng — lý do 1 câu: Không chỉ search mà còn bao hàm một hệ sinh thái mạnh mẽ (code, image, analysis) ở cùng mức giá.

---

## Phần E — Verdict sơ bộ (cho mục S5.1)

Đặt verdict 1 dòng cho mỗi sản phẩm (sẽ tinh chỉnh lại ở Bước 3 sau khi vận dụng 4 Lens + Spark/Loop/System):

- **Sản phẩm A — verdict sơ bộ**: Strong
  - Lý do 1 câu: Làm chủ hoàn toàn ngách AI Search với ARR tăng trưởng khủng ($450-500M) và giải quyết trọn vẹn "trust problem".
- **Sản phẩm B — verdict sơ bộ**: Strong
  - Lý do 1 câu: Vị thế quá lớn (900M WAU, $25B ARR) và Data flywheel khổng lồ giúp bảo vệ sản phẩm khỏi các rủi ro ngắn hạn.

---

## Bảng kiểm trước khi sang Bước 3

- [ ] Mỗi ô của bảng so sánh 5 mục có ít nhất 1-2 câu, không trống.
- [ ] Mỗi nhận định đều có thể chỉ về ảnh / log trong `1-research-notes.md` làm bằng chứng.
- [ ] Đã định vị cả 2 sản phẩm trên Cost-Capability-Speed.
- [ ] Đã có verdict sơ bộ cho cả 2 sản phẩm.
- [ ] Còn ô nào thiếu bằng chứng → đã đánh dấu để Phase 3 đào thêm.

Sang `3-FINAL-analysis-outline.md` để dựng outline 5 mục đầy đủ (với S5 mở rộng 8 sub-mục) trước khi build slide.
