---
artifact: group-members — Danh sách thành viên nhóm Lab 2
bai-tap: 2 — Phân tích sản phẩm AI (nhóm)
phase: Khai báo nhóm
nop-cuoi: Có — bắt buộc (nộp kèm analysis-report.pdf)
---

# Thành viên nhóm Lab 2

Lab 2 làm theo nhóm 2 học viên. Mỗi học viên có 1 repo riêng (`Day26-MãHọcViên`), nhưng nội dung Lab 2 (slide deck + screenshots + research notes) là sản phẩm chung — mỗi học viên copy bản chung về repo cá nhân của mình.

File này khai báo 2 thành viên trong nhóm + phân công thực hiện.

---

## Danh sách thành viên

| # | Mã học viên | Họ tên đầy đủ | Phân công chính |
|---|---|---|---|
| 1 | 2A202600423 | Quách Gia Được | Test Perplexity AI + chụp ảnh + S1, S2, S5.1, S5.6, S5.7 |
| 2 | 2A202600205 | Nguyễn Thành Nam | Test ChatGPT Search + chụp ảnh + S3, S4, S5.2-S5.5, S5.8 |

---

## Nhiệm vụ thử nghiệm chung

Cả 2 thành viên cùng test 2 sản phẩm AI search với cùng 1 câu prompt: **"Tỷ lệ thất nghiệp của sinh viên IT mới ra trường ở Việt Nam năm 2024 là bao nhiêu? Nguồn nào đáng tin nhất?"**

> Lý do chọn prompt: (1) Yêu cầu số liệu cụ thể → dễ kiểm chứng đúng/sai; (2) Chủ đề Việt Nam → test khả năng tiếng Việt; (3) Yêu cầu đánh giá nguồn → bộc lộ rõ khác biệt citation giữa 2 sản phẩm; (4) Là prompt gợi ý chính thức từ Track A.

**Ngành chọn**: A — Tìm kiếm

**Sản phẩm A**: Perplexity AI — https://www.perplexity.ai (Đã test trên gói Free)

**Sản phẩm B**: ChatGPT Search — https://chatgpt.com (Đã test trên gói Free)

---

## Phân chia screenshot

- Sản phẩm A (Perplexity AI) → Thành viên A phụ trách chụp (3 ảnh bắt buộc + 3 ảnh khuyến khích)
- Sản phẩm B (ChatGPT Search) → Thành viên B phụ trách chụp (3 ảnh bắt buộc + 3 ảnh khuyến khích)

---

## Ghi chú

- Mỗi thành viên copy folder `02-product-comparison/` (đã hoàn thiện) vào repo cá nhân của mình.
- Slide deck `analysis-report.pdf` và `analysis-report-link.md` (nếu có) là sản phẩm chung — 2 thành viên cùng tên trong credits của slide deck.
- File `group-members.md` này phải giống nhau ở cả 2 repo cá nhân (cùng nội dung, cùng 2 mã học viên).

---

## Cấu trúc Analysis Report — S5 mở rộng

Slide deck Analysis Report có 5 mục bắt buộc (S1 → S5). Mục S5 (Product Judgment) được mở rộng thành 8 mục con:

- **S5.1 Verdict** — mỗi sản phẩm xếp loại Strong / Promising / Weak / At Risk, kèm lý do 1 câu.
- **S5.2 User base + tăng trưởng** — số liệu công khai (MAU, DAU, paid users, growth rate) cho cả 2 sản phẩm + nguồn.
- **S5.3 Doanh thu / pricing power** — mức giá so với value cung cấp; ARR/MRR nếu công khai; pricing strategy (freemium, premium, enterprise).
- **S5.4 Moat phân tích** — đánh giá 5 loại moat (data / network / switching cost / brand / distribution) cho từng sản phẩm; moat nào mạnh, moat nào dễ bị copy.
- **S5.5 Data flywheel + feedback loop** — hành động người dùng nào feed lại model; loop có compounding không; sản phẩm có thu thập feedback systematically.
- **S5.6 Niche Down + AI Feature Map** — sản phẩm có niche rõ không; map User Value / User Alignment / Business Value cho từng sản phẩm.
- **S5.7 Spark → Loop → System** — mỗi sản phẩm đang ở giai đoạn nào; dự báo 12 tháng tới.
- **S5.8 Liên hệ Lab 1 case** — 2 sản phẩm có rủi ro disruption-style tương tự case Lab 1 không; bài học rút từ Lab 1 áp dụng được gì?

Nhóm bắt buộc xong S5.1, S5.6, S5.7, S5.8. S5.2–S5.5 là phần mở rộng cho phân tích sâu.
