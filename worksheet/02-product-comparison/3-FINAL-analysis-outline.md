---
artifact: 3 — Outline 5 mục cho slide deck Analysis Report
bai-tap: 2 — Phân tích 2 sản phẩm AI (nhóm 2 học viên)
phase: Phase 3 — Dựng slide deck (15 phút)
time: 10 phút outline + 5 phút build slide
input: 1-research-notes.md + 2-comparison-table.md + screenshots/ + prompts/08-analysis-report.md
nop-cuoi: Có gián tiếp — outline này dùng làm cốt cho `analysis-report.pdf` (deliverable bắt buộc)
---

# 3 — Outline 5 mục cho slide deck (S1 → S5 với S5 mở rộng 8 sub-mục)

## Thông tin chung của báo cáo

* **Mã 2 thành viên + tên**: [2A202600435 Trịnh Uyên Chi]
* **Ngành chọn**: [A — Tìm kiếm]
* **Nhiệm vụ chung đã test**: Phân tích thị trường trà sữa Việt Nam 2026.
* **Sản phẩm A** (tên + URL): Google Gemini ([https://gemini.google.com](https://gemini.google.com))
* **Sản phẩm B** (tên + URL): Perplexity ([https://www.perplexity.ai](https://www.perplexity.ai))
* **Câu prompt chính xác đã dùng**: *"Phân tích thị phần và chiến lược tăng trưởng của các chuỗi trà sữa lớn tại Việt Nam trong năm 2026. Trích dẫn ít nhất 3 nguồn tin cậy và cho biết xu hướng nào đang dẫn đầu (ví dụ: trà sữa thực dưỡng, giảm đường)."*

---

## S1 — Product Moment (slide 1-2)

### S1.1 — Bảng so sánh nhanh

| Yếu tố | Sản phẩm A: Gemini | Sản phẩm B: Perplexity |
| --- | --- | --- |
| Tên + URL | Google Gemini | Perplexity AI |
| Entry point | Giao diện tối giản, tập trung vào câu hỏi "Chúng ta cần tập trung vào nội dung gì?" | Thanh tìm kiếm trung tâm kèm các tab chuyên sâu (Academic, Finance) |
| Ý định người dùng | Tìm kiếm trợ lý vạn năng, thực hiện tác vụ đa năng (viết, code, search) | Tìm kiếm thông tin có dẫn nguồn, nghiên cứu sâu (Search & Cite) |
| Surface chính | Chat interface | Search-driven Chat interface |
| Paywall ngay không | Không, nhưng có nút "Nâng cấp" nổi bật | Có pop-up yêu cầu đăng nhập/sync ngay từ đầu |

### S1.2 — Bằng chứng (ảnh tham chiếu)

* `screenshots/product-A-1-entry.png` — Giao diện tiếng Việt hóa hoàn toàn, tích hợp sẵn nút chuyển model Pro.
* `screenshots/product-B-1-entry.png` — Giao diện tập trung vào tính năng "Computer" (Agentic) và các gợi ý xây dựng business.

### S1.3 — Nhận định so sánh entry point (2-3 câu)

Gemini tạo ấn tượng thân thiện và dễ tiếp cận hơn cho người dùng phổ thông nhờ ngôn ngữ bản địa hóa. Ngược lại, Perplexity khẳng định vị thế công cụ chuyên nghiệp ngay từ đầu với các tab nghiên cứu chuyên sâu (Academic/Patents).

---

## S2 — Workflow Evidence (slide 3-4)

### S2.1 — Luồng người dùng

**TRƯỚC khi gặp AI:**

* Người dùng tìm kiếm thủ công trên Google, mở 10-15 tab báo chí (Cafef, VnExpress), tự tổng hợp số liệu vào Excel/Docs.

**TRONG khi dùng Sản phẩm A (Gemini):**

1. Nhập prompt -> AI stream nội dung nhanh chóng.
2. Sử dụng "Debug Info" để kiểm tra logic.
3. Sử dụng gợi ý follow-up "Đi sâu vào chiến lược Mixue?" để đào sâu.

**TRONG khi dùng Sản phẩm B (Perplexity):**

1. Nhập prompt -> AI hiển thị quá trình "Searching the web" qua 20 nguồn.
2. Kiểm tra danh sách thẻ nguồn (citations) hiển thị ngay trên đầu.
3. Nhấp vào "Related" để mở rộng bản đồ nghiên cứu.

**SAU khi dùng AI:**

* Gemini: Xuất bảng biểu sang Google Sheets.
* Perplexity: Chia sẻ link nghiên cứu hoặc lưu vào Spaces để quản lý project.

### S2.2 — 3 Friction Areas (Lens 3)

| Friction | Sản phẩm A: Gemini | Sản phẩm B: Perplexity |
| --- | --- | --- |
| **Physical load** | Cần ít click hơn nhờ SSO Google; tích hợp nút Export trực tiếp. | Phải tắt pop-up đăng nhập; click nhiều để xem chi tiết từng nguồn dẫn. |
| **Cognitive burden** | Thấp; giao diện chat tự nhiên, không cần cấu hình phức tạp. | Trung bình; người dùng cần đánh giá độ tin cậy của 20 nguồn được dẫn. |
| **User workarounds** | Phải tự dùng "Double check" để xác thực lại số liệu nếu nghi ngờ hallucination. | Phải kiểm tra xem nguồn có bị chặn (paywall) hay không để đọc kỹ hơn. |

---

## S3 — Output & Trust (slide 5-6)

### S3.1 — Chất lượng output

* **Sản phẩm A (Gemini)**: Trả lời đúng, văn phong rất "người", thấu hiểu tâm lý thị trường Việt Nam (xu hướng "ít tội lỗi"). Tuy nhiên, thời gian xử lý thực tế có vẻ chậm hơn cảm giác stream (độ trễ ~2 phút theo log).
* **Sản phẩm B (Perplexity)**: Trả lời súc tích, tập trung hoàn toàn vào dữ liệu thực tế năm 2026. Khả năng tổng hợp từ 20 nguồn khác nhau giúp nội dung có độ khách quan cao.

### S3.2 — 6 Tín hiệu đáng tin (đối chiếu)

| Tín hiệu | Sản phẩm A: Gemini | Sản phẩm B: Perplexity |
| --- | --- | --- |
| 1. Dẫn nguồn | Một phần (Cần click "Double check") | **Có** (Hiển thị 20 nguồn minh bạch) |
| 2. Disclaimer | Có (Cố định ở footer) | Có (Dưới mỗi câu trả lời) |
| 3. Fallback | Trung bình; thỉnh thoảng trả lời chung chung | **Mạnh**; xác nhận nếu chưa có dữ liệu mới |
| 4. Consistency | Một phần (Mỗi lần chạy ra kết quả khác nhau) | Cao (Dựa trên index web cố định) |
| 5. User control | Mạnh (Sửa, dừng, chọn model Pro/Flash) | Mạnh (Share, export, follow-up) |
| 6. Explanation | **Có** (Tính năng "Debug Info") | **Có** (Hiển thị các bước search web) |

---

## S4 — Business Signal (slide 7)

### S4.1 — Định vị tam giác

* **Sản phẩm A**: **Cân bằng** — Dùng model Gemini 1.5 Pro. Lý do: Tốc độ xử lý khổng lồ của Google kết hợp khả năng suy luận đa phương tiện.
* **Sản phẩm B**: **Mạnh-Chuyên sâu** — Dùng model RAG kết hợp nhiều LLM. Lý do: Ưu tiên tính chính xác (Accuracy) và sự minh bạch của dữ liệu nghiên cứu.

### S4.2 — Pricing pattern

| Yếu tố | Sản phẩm A: Gemini | Sản phẩm B: Perplexity |
| --- | --- | --- |
| Mô hình giá | Freemium / Hybrid | Freemium / Subscription |
| Giá entry | Miễn phí (Gói cơ bản) | Miễn phí (Giới hạn Pro search) |
| Giá trả phí | ~$20/tháng (Gemini Advanced) | ~$20/tháng (Perplexity Pro) |
| Paywall | Khi dùng model Pro hoặc tính năng AI trong Workspace | Khi hết lượt Pro Search hàng ngày |

---

## S5 — Product Judgment (slide 8-12)

### S5.1 — Verdict (BẮT BUỘC)

* **Sản phẩm A**: **Promising** — Mạnh về hệ sinh thái và thấu hiểu văn hóa, nhưng cần "Grounded" dữ liệu tốt hơn để BA tin dùng tuyệt đối.
* **Sản phẩm B**: **Strong** — Sản phẩm search AI tiêu chuẩn cho nghiên cứu, giải quyết triệt để nỗi sợ Hallucination.

### S5.2 — User base + tăng trưởng

* **Sản phẩm A**: Ước tính hàng tỷ người dùng thông qua tích hợp Google Search và Android.
* **Sản phẩm B**: Đạt mốc **10 triệu MAU** (số liệu 2024) và đang tăng trưởng nóng trong cộng đồng trí thức.

### S5.3 — Doanh thu / pricing power

* **Sản phẩm A**: Bundled trong doanh thu Google Cloud/Workspace (Tỷ USD).
* **Sản phẩm B**: ARR ước tính đạt **~20-30 triệu USD** (2024-2025) và đang mở rộng gói Team/Enterprise.

### S5.4 — Moat phân tích (5 loại)

| Moat | Sản phẩm A: Gemini | Sản phẩm B: Perplexity |
| --- | --- | --- |
| Data | Mạnh (Google Index khổng lồ) | Trung bình (RAG trên web công khai) |
| Network effects | Yếu | Trung bình (Cộng đồng Discover/Spaces) |
| Switching cost | Trung bình (Dính chặt vào Workspace) | Trung bình (Dữ liệu lưu trong Spaces) |
| Brand | Mạnh (Google) | Trung bình (Vị thế AI Search tiên phong) |
| Distribution | **Cực mạnh** (Chrome, Android, Search) | Yếu (Dựa vào SEO và Word-of-mouth) |

### S5.6 — Niche Down + AI Feature Map (BẮT BUỘC)

* **Sản phẩm A**: Niche là người dùng hệ sinh thái Google (viết mail, tổng hợp Docs, search nhanh).
* **Sản phẩm B**: Niche là **Knowledge Workers** (BA, PM, Nhà nghiên cứu) cần dữ liệu chính xác có dẫn nguồn.

### S5.7 — Spark → Loop → System (BẮT BUỘC)

* **Sản phẩm A**: **System** — Đã là một phần của hệ điều hành toàn cầu. Dự báo 12 tháng tới: Tích hợp sâu AI vào mọi điểm chạm của Google.
* **Sản phẩm B**: **Loop** — Đang củng cố vòng lặp "Search -> Cite -> Share". Dự báo 12 tháng tới: Trở thành cổng vào tri thức thay thế Google cho nhóm chuyên gia.

### S5.8 — Liên hệ Lab 1 (BẮT BUỘC)

* Sản phẩm A và B đều đóng vai trò là "kẻ hủy diệt" đối với **Stack Overflow** (Lab 1) bằng cách cung cấp câu trả lời tại chỗ, bẻ gãy hành vi Search-and-Browse truyền thống.
* **Bài học**: Khi kỳ vọng người dùng chuyển sang "Do the work for me" (Shift 1), các nền tảng dựa trên lưu lượng (Traffic-based) như Stack Overflow buộc phải bán dữ liệu cho chính các sản phẩm AI này để tồn tại.
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
