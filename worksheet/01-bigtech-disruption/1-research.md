---
artifact: 1 — Tự nghiên cứu case
bai-tap: 1 — Tìm 1 case bị ảnh hưởng bởi big tech AI (cá nhân)
phase: Chọn case + tìm số liệu + nguồn
time: 15 phút (xem deck slide 4 để biết khung giờ chính xác trong buổi)
input: prompts/01-research-case.md
nop-cuoi: Không — file trung gian
---

# 1 — Tự nghiên cứu: Case Stack Overflow vs. Generative AI

* **Tên case**: Stack Overflow
* **Big tech AI tạo áp lực**: OpenAI (ChatGPT) & GitHub/Microsoft (GitHub Copilot)
* **Lý do chọn**: Đây là case điển hình nhất về việc "tính tiện dụng" của AI hủy diệt mô hình "cộng đồng tra cứu" truyền thống. Số liệu về sự sụt giảm lưu lượng truy cập và phản ứng nhân sự của Stack Overflow rất minh bạch và có tính thời điểm rõ ràng.

---

## PHẦN B — BẢNG TỔNG HỢP SỐ LIỆU

| # | Số liệu | Giá trị | Ngày / Thời kỳ | Nguồn (URL) | Đã kiểm chứng? |
| --- | --- | --- | --- | --- | --- |
| **S-01** | Định giá khi được mua lại (Prosus) | 1,8 tỷ USD | 02/06/2021 | [Prosus Official](https://www.google.com/search?q=https://www.prosus.com/news/prosus-to-acquire-stack-overflow-for-us1-8-billion/) | ✅ verified |
| **S-02** | Lưu lượng truy cập (Traffic) sụt giảm | ~14% (trong 1 tháng) | Tháng 03/2023 | [Similarweb Blog](https://www.similarweb.com/blog/insights/ai-news/stack-overflow-chatgpt/) | ✅ verified |
| **S-03** | Big tech AI ra mắt (ChatGPT) | Public Launch | 30/11/2022 | [OpenAI Blog](https://openai.com/blog/chatgpt) | ✅ verified |
| **S-04** | Big tech AI ra mắt (GitHub Copilot) | General Availability | 21/06/2022 | [GitHub Blog](https://www.google.com/search?q=https://github.blog/2022-06-21-github-copilot-is-generally-available-to-all-software-developers/) | ✅ verified |
| **S-05** | Sản phẩm AI phản ứng (OverflowAI) | Công bố | 27/07/2023 | [Stack Overflow Blog](https://www.google.com/search?q=https://stackoverflow.blog/2023/07/27/announcing-overflow-ai/) | ✅ verified |
| **S-06** | Khoảng cách thời gian (ChatGPT → OverflowAI) | **8 tháng** | 11/2022 - 07/2023 | Đối soát S-03 & S-05 | ✅ verified |
| **S-07** | Đợt sa thải nhân sự lớn nhất | **28% nhân sự** | 16/10/2023 | [CNBC](https://www.google.com/search?q=https://www.cnbc.com/2023/10/16/stack-overflow-lays-off-28percent-of-staff-as-ai-threatens-traffic.html) | ✅ verified |
| **S-08** | Số lượng câu hỏi mới sụt giảm | ~16% | Tháng 07/2023 | [The Verge](https://www.google.com/search?q=https://www.theverge.com/2023/7/24/23805915/stack-overflow-traffic-decline-chatgpt-generative-ai) | ✅ verified |
| **S-09** | Đối thủ startup mới (Cursor AI) | Series B ($400M valuation) | 08/2024 | [TechCrunch](https://www.google.com/search?q=https://techcrunch.com/2024/08/21/ai-code-editor-cursor-raises-60m-series-a-at-a-400m-valuation/) | ✅ verified |
| **S-10** | Hợp đồng dữ liệu với OpenAI | Hợp tác API & Data | 04/05/2024 | [OpenAI News](https://www.google.com/search?q=https://openai.com/index/openai-and-stack-overflow-partnership/) | ✅ verified |

---

## PHẦN D — PHÁT HIỆN BAN ĐẦU (INSIGHTS)

* **Sự sụt giảm kép**: Stack Overflow không chỉ mất người xem (traffic) mà còn mất cả người đóng góp (contributors). Số lượng câu hỏi mới giảm 16% cho thấy "nguồn sống" của một nền tảng crowdsourcing đang bị đe dọa nghiêm trọng.
* **Độ trễ chiến lược (8 tháng)**: Trong khi thế giới developer thay đổi hàng tuần, việc mất 8 tháng để ra mắt bản giới thiệu OverflowAI là quá chậm. Khi Stack Overflow ra tính năng, thói quen "Copy-Paste từ ChatGPT" đã hình thành xong.
* **Mâu thuẫn nội tại**: Cuộc đình công của các Moderator vào tháng 06/2023 cho thấy sự xung đột giữa việc duy trì chất lượng "do người làm" và áp lực phải dùng AI để cạnh tranh.
* **Chuyển dịch mô hình kinh doanh**: Việc ký hợp đồng với OpenAI (S-10) cho thấy Stack Overflow đang chấp nhận từ bỏ vị thế "điểm đến của người dùng" để trở thành "kho thức ăn cho mô hình AI" (Data provider).

---

## PHẦN E — CÂU HỎI MỞ (CHO PHẦN 2)

* **Câu hỏi 1**: Tại sao người dùng sẵn sàng tin vào câu trả lời có thể bị "hallucination" của AI hơn là câu trả lời đã được cộng đồng vote trên Stack Overflow? (Phân tích Customer Expectations).
* **Câu hỏi 2**: Việc sa thải 28% nhân sự là để tối ưu chi phí hay là dấu hiệu của việc mô hình kinh doanh dựa trên quảng cáo (Ads) đã sụp đổ khi traffic giảm?
* **Câu hỏi 3**: OverflowAI có thực sự giải quyết được bài toán "Four Fits" khi mà nó vẫn yêu cầu người dùng phải truy cập vào một website riêng biệt thay vì tích hợp trực tiếp vào IDE như GitHub Copilot?
* **Câu hỏi 4**: Liệu việc bán dữ liệu cho OpenAI có phải là "tự sát" lâu dài (cannibalization) khi làm cho đối thủ ChatGPT ngày càng thông minh hơn và người dùng càng ít cần đến Stack Overflow hơn?

---