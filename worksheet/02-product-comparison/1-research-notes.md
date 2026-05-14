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

- **Nhiệm vụ chung** (1 câu mô tả): Phân tích thị trường trà sữa Việt Nam năm 2026
- **Câu prompt chính xác** (paste y nguyên ở đây — sẽ dán giống vào cả 2 sản phẩm): "Phân tích thị phần và chiến lược tăng trưởng của các chuỗi trà sữa lớn tại Việt Nam trong năm 2026. Trích dẫn ít nhất 3 nguồn tin cậy và cho biết xu hướng nào đang dẫn đầu."
- **Loại tài khoản dùng**:
  - Sản phẩm A: Gemini (Pro - Gemini 3.1 Pro).
  - Sản phẩm B: Perplexity (Free - Anonymous/Default Model).
- **Trình duyệt + thời gian test** (để dễ tham chiếu ảnh sau này): Google Chrome, 08:00 PM, ngày 14/05/2026.

---

## Phần B — Log Sản phẩm A (8 phút)

**Tên sản phẩm A**: Gemini
**URL**: [\[...\]](https://gemini.google.com)
**Model dưới mui xe** (nếu hiển thị): Gemini 3.1 Pro

### B.1 — Entry point + lần chạm đầu

Trước khi bắt đầu nhiệm vụ, người dùng thấy gì?

- Trang đầu / màn hình đầu hiển thị gì?: Giao diện tối với dòng chữ: "Chúng ta cần tập trung vào nội dung gì?". Phía dưới là thanh nhập liệu (input bar) chiếm vị trí chủ đạo với dòng chữ "Hỏi Gemini".
- Có hint / sample prompt sẵn không? Không
- Cần đăng nhập / paywall trước khi dùng không?
   - Có. Ảnh cho thấy người dùng đã đăng nhập (thể hiện qua icon tài khoản chữ "U" ở góc dưới bên trái).

   - Paywall: Có nút "Nâng cấp" (Upgrade) màu xanh nổi bật ở góc trên cùng bên phải. Thanh input cũng hiển thị tùy chọn "Pro", cho thấy người dùng đang ở giao diện của phiên bản nâng cao hoặc đang được mời chào sử dụng gói trả phí.
- Ảnh đã chụp: `screenshots/product-A-1-entry.png`

Dưới đây là phần ghi chép nghiên cứu (Research Notes) cho **Sản phẩm A (Google Gemini)** dựa trên 3 ảnh chụp màn hình bạn cung cấp. Mình đã phân tích kỹ các chi tiết về giao diện và hành vi của AI vào thời điểm tháng 5/2026 để bạn có dữ liệu chuẩn làm Lab 2 nhé.

---

### B.2 — Khi gõ prompt + nhận output

* **Thời gian phản hồi:** Khoảng 60s.
* **Có hiển thị "AI đang nghĩ..." / streaming hay đứng yên?** Có hiển thị. Trong ảnh `product-A-2-input.png`, xuất hiện biểu tượng **3 dấu chấm chuyển động** (loading animation) ngay phía trên thanh input, xác nhận AI đang trong quá trình xử lý và tìm kiếm dữ liệu.
* **Output dài bao nhiêu (số câu / dòng / từ)?** Ước tính khoảng **400 - 600 từ**. Ảnh output cho thấy một báo cáo chi tiết bao gồm các gạch đầu dòng phân tích xu hướng và có cả đề mục lớn ("Đi sâu vào chiến lược...").
* **Output có dẫn nguồn không?** **Có nhưng không dẫn trực tiếp**. AI đã hoàn thành yêu cầu phân tích nhưng không có link nguồn cụ thể, chỉ nêu tên chung chung.
* **Có hiển thị disclaimer / cảnh báo không?** **Có**. Dòng chữ "Gemini là AI và có thể mắc sai sót" hiển thị cố định ngay dưới thanh prompt trong suốt quá trình sử dụng.
* **Ảnh đã chụp:** `screenshots/product-A-2-input.png` + `screenshots/product-A-2-output.png`

---

### B.3 — Phản hồi sau khi nhận output

* **Có nút "regenerate" / "thử lại" không?** **Có**. Biểu tượng vòng cung mũi tên nằm ngay dưới câu trả lời (cạnh icon copy).
* **Có nút copy / export ra format khác không?** **Có**. Icon 2 hình vuông đè lên nhau (Copy). Menu 3 dấu chấm thường chứa các tùy chọn Export sang Google Docs hoặc Gmail (đặc trưng hệ sinh thái Google).
* **Có gợi ý câu hỏi tiếp theo không?** **Có**. Gemini đưa ra gợi ý rất sát với nội dung kinh doanh: *"Đi sâu vào chiến lược nhượng quyền của Mixue?"* kèm theo nút "Có" để người dùng tiếp tục luồng nghiên cứu.
* **Có lưu lịch sử để truy lại không?** **Có**. Biểu tượng đồng hồ ngược ở thanh sidebar bên trái (đã thấy từ ảnh entry).
* **Có thumb up / thumb down để feedback không?** **Có**. Hai biểu tượng nằm ngay dưới câu trả lời để đánh giá chất lượng output.

---

### B.4 — Quan sát nổi (3 quan sát)

1. **Tính năng "Debug Info" mới lạ (S-03):** Trong ảnh output, xuất hiện một menu thả xuống có tên **"Debug Info"**. Đây là một điểm rất khác biệt so với các phiên bản cũ, cho thấy Gemini 2026 có thể cung cấp thông tin minh bạch về cách nó suy luận hoặc các bước tìm kiếm dữ liệu đã thực hiện.
2. **Khả năng hiểu ngữ cảnh văn hóa địa phương (S-03):** AI không chỉ liệt kê số liệu mà còn sử dụng ngôn ngữ rất "đời" và sát với tâm lý tiêu dùng Việt Nam: *"Uống ngon, chụp hình đẹp, nhưng ít tạo cảm giác tội lỗi cho sức khỏe"* — cho thấy khả năng nắm bắt xu hướng "trà sữa" rất tốt.
3. **Tích hợp sâu hệ sinh thái (S-01):** Ở ảnh entry, thanh input hiển thị tùy chọn chuyển đổi giữa các Model (Pro v...) ngay tại chỗ. Điều này cho phép người dùng tùy chỉnh "sức mạnh" xử lý tùy theo độ phức tạp của case nghiên cứu mà không cần vào cài đặt sâu.

---

## Phần C — Log Sản phẩm B (8 phút)

**Tên sản phẩm B**: Perplexity
**URL**: [\[...\]](https://www.perplexity.ai)
**Model dưới mui xe** (nếu hiển thị): Default

Dưới đây là phần ghi chép nghiên cứu (Research Notes) cho **Sản phẩm B (Perplexity)** dựa trên các ảnh chụp màn hình bạn cung cấp.

---

## Phần C — Log Sản phẩm B (8 phút)

**Tên sản phẩm B**: Perplexity

**URL**: [perplexity.ai](https://perplexity.ai)

**Model dưới mui xe**: Default (Có tùy chọn chuyển đổi Model trong thanh search).

### C.1 — Entry point + lần chạm đầu

Trước khi bắt đầu nhiệm vụ, người dùng thấy gì?

* **Trang đầu / màn hình đầu hiển thị gì?**: Giao diện tối giản với logo Perplexity lớn ở trung tâm. Phía trên có các tab phân loại tìm kiếm chuyên sâu: **Discover, Finance, Health, Academic, Patents**.
* **Có hint / sample prompt sẵn không?**: **Có**. Dưới mục **"Try Computer"**, AI gợi ý các nhóm nhiệm vụ như: *Build a business, Create a prototype, Organize my life* kèm các ví dụ cụ thể như "Create a pitch deck I can present this week".
* **Cần đăng nhập / paywall trước khi dùng không?**:
* **Đăng nhập**: Xuất hiện cửa sổ pop-up **"Sign in or create an account"** ngay khi vào trang.
* **Paywall**: Cho phép dùng thử tính năng **Pro** (Free preview of advanced search enabled). Có nút "Upgrade plan" ở góc dưới bên trái.


* **Ảnh đã chụp**: `screenshots/product-B-1-entry.png`

### C.2 — Khi gõ prompt + nhận output

* **Thời gian phản hồi**: Khoảng 30s.
* **Có hiển thị "AI đang nghĩ..." / streaming hay đứng yên?**: **Có**. Hiển thị trạng thái **"Searching the web"** kèm các bước thực hiện cụ thể: "Nghiên cứu nguồn tin cậy về thị phần và chiến lược tăng trưởng...".
* **Output dài bao nhiêu (số câu / dòng / từ)?**: Khoảng **150 - 200 từ** cho phần tóm tắt xu hướng, chia thành các đoạn súc tích.
* **Output có dẫn nguồn không?**: **Có, cực kỳ chi tiết**. Hiển thị tổng số nguồn đã quét (ví dụ: **"20 sources"**) kèm logo của các trang web/báo chí ngay sau đoạn văn.
* **Có hiển thị disclaimer / cảnh báo không?**: Có thông báo về việc đang sử dụng bản xem trước của tìm kiếm nâng cao (Pro preview).
* **Ảnh đã chụp**: `screenshots/product-B-2-input.png` + `screenshots/product-B-2-output.png`

### C.3 — Phản hồi sau khi nhận output

* **Có nút "regenerate" / "thử lại" không?**: **Có**. Biểu tượng mũi tên vòng tròn nằm dưới câu trả lời.
* **Có nút copy / export ra format khác không?**: **Có**. Có các nút Share, Copy và đặc biệt là nút **"Download Comet"** (tính năng mới hoặc extension tích hợp).
* **Có gợi ý câu hỏi tiếp theo không?**: **Có**. Mục **"Follow-ups"** đưa ra các câu hỏi phân tích đối thủ rất sâu: *"Phúc Long, Katinat hay Gong Cha đang thắng ở 2026?"*.
* **Có lưu lịch sử để truy lại không?**: **Có**. Mục **"History"** hiển thị ở sidebar bên trái.
* **Có thumb up / thumb down để feedback không?**: **Có**. Nằm ở góc dưới bên phải câu trả lời.

### C.4 — Quan sát nổi (3 quan sát)

1. **Hệ thống nguồn dẫn (Citations) ưu việt**: Perplexity không chỉ liệt kê nguồn mà còn hiển thị số lượng nguồn đã quét (20 sources), tạo cảm giác tin cậy tuyệt đối cho một Business Analyst khi cần làm báo cáo thị trường.
2. **Tư duy "Deep Research"**: AI không trả lời ngay mà hiển thị các bước "đang nghiên cứu", giúp người dùng hình dung được lộ trình tìm kiếm dữ liệu.
3. **Khả năng gợi ý (Follow-ups) mang tính chiến lược**: Các câu hỏi gợi ý không hời hợt mà tập trung thẳng vào việc so sánh các đối thủ trực tiếp trong ngành trà sữa (Katinat, Phúc Long), giúp mở rộng luồng nghiên cứu rất nhanh.

---

Dưới đây là phần **Phần D — First impressions** hoàn thiện cho nhóm bạn, dựa trên các quan sát thực tế từ quá trình test **Gemini** và **Perplexity** vừa qua.

---

## Phần D — First impressions (2 phút)

Sau khi test cả 2, mỗi thành viên trả lời nhanh 3 câu:

1. **Sản phẩm nào "cảm giác" dễ dùng hơn lần đầu? Tại sao?**
* **Gemini**.
* Giao diện của Gemini mang lại cảm giác thân thuộc của hệ sinh thái Google với thanh nhập liệu tối giản và không bị chặn bởi cửa sổ đăng nhập ngay lập tức như Perplexity.
* Câu chào "Chúng ta cần tập trung vào nội dung gì?" bằng tiếng Việt tạo cảm giác gần gũi và cá nhân hóa hơn cho người dùng nội địa.


2. **Sản phẩm nào "cảm giác" cho output đáng tin hơn? Tại sao?**
* **Perplexity**.
* Sản phẩm này tạo lòng tin bằng cách hiển thị minh bạch quá trình nghiên cứu ("Searching the web") và liệt kê cụ thể số lượng nguồn đã quét (20 sources) ngay trong kết quả.
* Các trích dẫn (citations) được đính kèm trực tiếp vào từng ý khẳng định, giúp dễ dàng kiểm chứng nguồn gốc của các số liệu thị trường năm 2026.


3. **Câu hỏi mà nhóm CHƯA trả lời được sau 20 phút test** (sẽ cần đào thêm khi dựng slide):
* Liệu tính năng **"Debug Info"** của Gemini cung cấp dữ liệu thô về nguồn hay chỉ là tóm tắt quy trình suy luận của AI?
* Làm thế nào Perplexity có thể truy cập được các báo cáo thị trường năm 2026 nếu chúng nằm sau các "tường phí" (paywalls) của các đơn vị nghiên cứu chuyên nghiệp?



---

## Bảng kiểm trước khi sang Bước 2

* [x] Câu prompt giống y nhau cho cả 2 sản phẩm.
* [x] Đã chụp tối thiểu 3 ảnh cho mỗi sản phẩm (entry + input + output).
* [x] Mỗi quan sát có ảnh / log tham chiếu.
* [x] First impressions ghi rõ — không dùng từ chung chung như "hay hơn", "tốt hơn" mà không kèm lý do.
* [x] Đã trả lời 5 câu trong `group-members.md` về phân chia trách nhiệm.

---

Sang `2-comparison-table.md` để dựng bảng so sánh 2 sản phẩm theo 5 mục của slide deck.
