---
artifact: 2 — Phân tích case theo 4 câu hỏi
bai-tap: 1 — Tìm 1 case bị ảnh hưởng bởi big tech AI (cá nhân)
phase: Vận dụng Lens 1 (Customer Expectations + Four Fits)
time: 15 phút
input: 1-research.md + prompts/02-four-fits-analysis.md
nop-cuoi: Không — file trung gian
---

# 2 — Phân tích case: Phần A (4 câu hỏi chiến lược) + Phần B (5 chiều phân tích)

Quy tắc: mỗi câu trả lời phải tham chiếu ít nhất 2 số liệu từ `1-research.md`.

---

# Phần A — 4 câu hỏi chiến lược

## Câu hỏi 1 — Trước AI, sản phẩm hoạt động dựa trên giả định gì?

### Trả lời

- **Người dùng**: Marketer, designer, content creator, doanh nghiệp cần hình ảnh chuyên nghiệp cho quảng cáo, website, social media, ấn phẩm
- **Vấn đề người dùng cần giải**: Cần hình ảnh chất lượng cao, hợp pháp (đã mua license), sẵn sàng dùng ngay — không cần thuê photographer
- **Giá trị sản phẩm cung cấp**: Thư viện 500M+ ảnh/video/nhạc có license sẵn, tìm kiếm bằng keyword, download ngay tức thì
- **Mô hình kinh doanh**: Subscription ($29-149/tháng) + pay-per-download. Chia sẻ doanh thu với contributors (photographers)
- **Vì sao mô hình này hoạt động**:
  - Lý do 1: Tự thuê photographer tốn $500-5000/buổi chụp → mua ảnh stock $0.25-15/ảnh rẻ hơn 100x
  - Lý do 2: Thư viện 500M+ ảnh → luôn tìm được ảnh phù hợp cho bất kỳ nhu cầu nào
  - Lý do 3: Legal protection — ảnh stock có license rõ ràng, tránh rủi ro bản quyền

**Bằng chứng**:

- [S-07]: Doanh thu 2024 đạt $935M — chứng minh mô hình từng hoạt động ở quy mô rất lớn
- [S-16]: Giá subscription $29-149/tháng — model pricing cho thấy willingness to pay cao

---

## Câu hỏi 2 — Kỳ vọng của người dùng đã thay đổi như thế nào?

### Trả lời

Các shift quan trọng nhất trong case Shutterstock:

- **Shift số 1**: Do the work for me — Trước: người dùng tìm ảnh trong thư viện → chấp nhận ảnh "gần đúng". Sau AI: gõ prompt → nhận ảnh CHÍNH XÁC theo ý muốn
- **Shift số 2**: Custom made for me — Trước: chọn từ ảnh có sẵn (generic). Sau AI: mỗi ảnh tạo riêng cho từng project, màu sắc, phong cách, bố cục theo yêu cầu
- **Shift số 5**: Expect it now — Trước: tìm kiếm 15-30 phút trong thư viện triệu ảnh. Sau AI: gõ 1 câu, có ảnh trong 10 giây

| Trước AI (kỳ vọng cũ) | Sau AI (kỳ vọng mới) |
|---|---|
| Tìm ảnh "office meeting" → chọn 1 trong 50,000 kết quả generic | Gõ "Vietnamese team meeting in modern glass office, warm lighting, 4 people smiling" → ảnh chính xác |
| Chấp nhận ảnh có watermark → mua license → download | Tạo ảnh miễn phí bằng Stable Diffusion hoặc $20/tháng DALL-E unlimited |
| Cần ảnh cho blog → mua subscription $29/tháng (10 ảnh) | Cần ảnh → mở ChatGPT/Midjourney → tạo unlimited ảnh tùy chỉnh |
| Lo bản quyền → chỉ dùng ảnh stock có license | Adobe Firefly tạo ảnh "commercially safe" (trained on licensed data) |

**Bằng chứng**:

- [S-04, S-05]: DALL-E 2 (04/2022) + Stable Diffusion (08/2022) ra mắt cùng năm → tạo "new normal" cho expectation
- [S-12]: Subscribers giảm 8% (1,079K→993K) — người dùng rời bỏ ảnh stock
- [S-11]: Subscribers giảm 8% (1.08M→993K) — người dùng rời bỏ ảnh stock

---

## Câu hỏi 3 — Giả định nào của sản phẩm đã không còn đúng?

### Trả lời

Sau khi AI image generation ra mắt, các Fit đã vỡ:

1. **Fit vỡ đầu tiên: PMF** — Sản phẩm (ảnh stock generic) không còn giải đúng nhu cầu khi người dùng muốn ảnh TÙY CHỈNH, không phải ảnh CÓ SẴN
   - Bằng chứng: [S-12] Content revenue giảm 12% YoY (Q1 2026)

2. **Fit vỡ thứ hai: MMF** — Mô hình subscription $29-149/tháng (giới hạn downloads) không cạnh tranh được với AI $0-20/tháng (unlimited ảnh tùy chỉnh)
   - Bằng chứng: [S-16 vs S-17] Shutterstock $29-149/tháng vs Midjourney $10-60/tháng unlimited

3. **Fit vỡ thứ ba: PCF** — Kênh phân phối (SEO + Google Images referral) bị AI tools bypass — người dùng không search "stock photo" nữa, họ gõ prompt trực tiếp
   - Bằng chứng: [S-11] Subscribers giảm → kênh thu hút khách mới yếu đi

4. **Fit vỡ thứ tư: CMF** — Chi phí duy trì thư viện 500M+ ảnh + trả royalties cho contributors cao, trong khi AI tạo ảnh gần như zero marginal cost
   - Bằng chứng: [S-10] Lỗ -$47.6M Q1 2026 — chi phí cao hơn doanh thu

Tốc độ vỡ Fit:

- Từ DALL-E 2 (04/2022) đến khi subscribers giảm rõ (Q1 2026): ~48 tháng
- Nhưng cổ phiếu đã giảm 85% trong giai đoạn này — thị trường "price in" disruption nhanh hơn doanh thu thể hiện
- Kết luận: **đã** trải qua Fit Collapse — chậm hơn Chegg nhưng chắc chắn hơn

**Bằng chứng**: [S-01→S-02] Cổ phiếu từ $107→$16, [S-09→S-10] Revenue -18% + lỗ $47.6M Q1 2026

---

## Câu hỏi 4 — Sản phẩm có thể cứu vãn? Hay đã quá muộn?

### Trả lời

So sánh Shutterstock với đối thủ phản ứng tốt hơn — **Adobe**:

| Yếu tố | Shutterstock | Adobe |
|---|---|---|
| Đối tác AI | Bán data cho OpenAI → train DALL-E (đối thủ) | Tự phát triển Firefly (trained on licensed data) |
| Thời gian ra sản phẩm AI | 1 tháng (nhanh nhưng dùng công nghệ đối thủ) | 12 tháng (chậm nhưng tự chủ công nghệ) |
| Giá sản phẩm AI | Gắn vào subscription cũ ($29+) | Tích hợp vào Photoshop ($23/tháng — đã có sẵn) |
| Tích hợp workflow | AI generator tách biệt khỏi workflow chính | AI tích hợp trực tiếp trong Photoshop/Illustrator → zero switching cost |
| Mô hình kinh doanh | Vẫn phụ thuộc subscription ảnh stock | Subscription phần mềm + AI = giá trị tăng thêm (không mất doanh thu cũ) |

Big Squeeze trên Shutterstock (3 lực nén):

- **Lực 1 — Doanh nghiệp lớn**: Adobe Firefly tích hợp vào Creative Cloud → designer dùng AI trong workflow quen thuộc, không cần Shutterstock
- **Lực 2 — Startup khác**: Midjourney ($10/tháng, chất lượng nghệ thuật top), Leonardo.ai, Ideogram — tạo ảnh tùy chỉnh rẻ và đẹp hơn ảnh stock
- **Lực 3 — Platform AI**: DALL-E 3 tích hợp ChatGPT (900M WAU) → bất kỳ ai cũng tạo ảnh ngay trong ChatGPT

Đánh giá:

- **Sản phẩm có cứu vãn được không?**: Có nhưng phải thay đổi hoàn toàn — từ "bán ảnh stock" sang "cung cấp visual content infrastructure"
- **Lý do**:
  - Lý do 1: Ảnh stock generic sẽ chết — AI tạo rẻ hơn, nhanh hơn, tùy chỉnh hơn
  - Lý do 2: Niche còn sống: editorial (ảnh sự kiện thật), authenticated (người thật), culturally specific (ảnh Việt Nam authentic) — AI chưa thay thế được
  - Lý do 3: Merger với Getty = defensive consolidation, không phải growth strategy
- **Điều đáng lẽ phải làm khác**:
  - Tự xây AI model thay vì bán data cho OpenAI
  - Tích hợp AI generation vào workflow designer (như Adobe làm)
  - Chuyển mô hình từ "bán ảnh" sang "bán công cụ sáng tạo visual AI"

**Bằng chứng**: [S-06] Bán data cho OpenAI = self-disruption, [S-14] Merger Getty = defensive move

---

# Phần B — 5 chiều phân tích định lượng

## B1 — User base

| Chỉ số | Trước AI shock | Sau AI shock | Nguồn |
|---|---|---|---|
| Paid subscribers | ~1,200K+ (ước tính 2022) | 993K (Q1 2026) | [Shutterstock IR](https://investor.shutterstock.com/) |
| Contributors | 2M+ photographers | Earnings giảm, nhiều rời bỏ | Contributor forums |
| ARPC | ~$244 (Q1 2025) | $284 (Q1 2026, tăng vì mất khách nhỏ) | [StockTitan](https://stocktitan.net/) |

Nhận định: Khách nhỏ (bloggers, SMB) rời bỏ nhanh nhất vì AI tools rẻ hơn. Khách lớn (enterprise) vẫn ở lại vì cần license rõ ràng → ARPC tăng nhưng tổng subscribers giảm. Đây là "shrinking to premium" — nguy hiểm vì base bị thu hẹp.

## B2 — Tốc độ tăng trưởng

| Giai đoạn | Tốc độ | Nguồn |
|---|---|---|
| Pre-AI (2021-2022) | Ổn định, cổ phiếu đỉnh $107 | Macrotrends |
| 2023-2024 | Revenue +7% (nhờ Envato acquisition + AI licensing) | Shutterstock IR |
| 2024-2025 | Revenue +6% (AI licensing tăng bù content giảm) | Shutterstock IR |
| Q1 2026 | Revenue -18% YoY — sụp đổ | StockTitan |
| Đảo chiều thực sự | Q1 2026 — khi cả content (-12%) và DDS (-47%) đều giảm | StockTitan |

Nhận định: Shutterstock "che giấu" suy giảm bằng acquisition (Envato) và AI data licensing. Q1 2026 là lúc mọi thứ sụp — cả 2 segment đều giảm cùng lúc.

## B3 — Doanh thu / valuation

| Chỉ số | Trước AI shock | Sau AI shock | Nguồn |
|---|---|---|---|
| Market cap | ~$4.07B (10/2021) | ~$600M (05/2026) | CompaniesMarketCap |
| Revenue | $935M (2024) | $199M Q1 2026 (-18% YoY) | Shutterstock IR |
| Net income → loss | +$18.7M (Q1 2025) | -$47.6M (Q1 2026) | StockTitan |

Mức công khai: Có — niêm yết NYSE, báo cáo SEC hàng quý.

Nhận định: Market cap giảm 87% trong 4 năm. Revenue tổng vẫn tăng nhờ acquisitions nhưng "organic" content revenue đang sụp → Q1 2026 là "breaking point".

## B4 — Moat strategy

| Loại moat | Mức mạnh trước AI | Bằng chứng |
|---|---|---|
| Data moat | Mạnh → Trung bình | 500M+ ảnh/video — nhưng AI tạo ảnh mới unlimited, data cũ mất giá trị |
| Network effect | Trung bình | Nhiều contributor → nhiều ảnh → nhiều khách. Nhưng 2-sided marketplace effect yếu đi khi contributor earnings giảm |
| Switching cost | Trung bình | Enterprise contracts có lock-in. Nhưng cá nhân/SMB chuyển sang AI dễ dàng |
| Brand | Mạnh | "Shutterstock" = stock photos. Nhưng brand gắn với "ảnh stock" — khi market shift sang AI, brand trở thành liability |
| Distribution | Trung bình | SEO + API integrations (WordPress, Canva plugins). Nhưng bị AI tools bypass |

- **Moat chủ đạo trước AI**: Data moat (500M+ ảnh có license) — thư viện lớn nhất thế giới
- **Big tech AI tấn công moat nào**: Data moat — AI không cần thư viện ảnh có sẵn, nó TẠO ảnh mới. 500M ảnh trở thành chi phí lưu trữ thay vì lợi thế cạnh tranh
- **Moat vẫn còn**: Brand + Enterprise switching cost — doanh nghiệp lớn vẫn cần ảnh có legal license rõ ràng

Nhận định: Moat "data" của Shutterstock bị AI vô hiệu hoá theo cách chưa từng thấy: thay vì đối thủ cần data lớn hơn (traditional competition), AI tạo data mới unlimited → toàn bộ thư viện mất giá trị cạnh tranh.

## B5 — Data flywheel + feedback loop

- **Hành động người dùng feed lại model**: Search queries → improve search relevance; download patterns → curate trending content
- **Loop có compounding**: Một phần — nhiều contributor → nhiều ảnh → nhiều khách → nhiều revenue share → thu hút thêm contributor. NHƯNG loop bị phá vỡ khi contributor earnings giảm → contributors rời bỏ
- **Thu thập feedback systematically**: Có (download tracking, search analytics, A/B testing)
- **Big tech AI vô hiệu hoá flywheel ở đâu**: Cắt đứt ở "nhiều khách" — khi khách chuyển sang AI generate, ít khách hơn → ít revenue share → ít contributor → ít ảnh mới → ít giá trị → more khách rời bỏ = **death spiral**

Nhận định: Flywheel Shutterstock (contributor → content → customer → revenue → contributor) bị AI tạo **reverse flywheel** (death spiral). Khi customers rời bỏ, contributors cũng rời bỏ, tạo vòng lặp âm ngày càng nhanh.

---

## Tổng kiểm tra

| Phần | Đã trả lời chưa? | Có ít nhất 2 bằng chứng? |
|---|---|---|
| A — Câu 1 — Giả định cũ | ✅ | ✅ (S-07, S-16) |
| A — Câu 2 — Kỳ vọng thay đổi | ✅ | ✅ (S-04, S-05, S-11) |
| A — Câu 3 — Fit nào vỡ | ✅ | ✅ (S-12, S-16, S-17, S-11, S-10, S-01, S-02, S-09) |
| A — Câu 4 — Cứu được không | ✅ | ✅ (S-06, S-14) |
| B1 — User base | ✅ | ✅ |
| B2 — Tốc độ tăng trưởng | ✅ | ✅ |
| B3 — Doanh thu / valuation | ✅ | ✅ |
| B4 — Moat strategy | ✅ | ✅ |
| B5 — Data flywheel | ✅ | ✅ |

Sau bước này, chuyển sang `3-FINAL-case-analysis.md`.
