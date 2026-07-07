# Tài liệu học viên — Workshop Lập đội ngũ AI Agent cho Sale & Marketing

> Bạn giữ file này để làm theo trong buổi và tự dựng lại sau buổi.

## Bạn sẽ làm được gì
- Hiểu một đội AI Agent cho Sale & Marketing gồm những vai trò nào.
- Tự dựng 2 agent: Discovery Agent (hiểu khách) và Customer Insight Agent (ra insight từ dữ liệu).
- Nắm nguyên tắc chống bịa và human review để dùng AI an toàn trong công việc thật.

## Chuẩn bị (làm trước buổi)
- Máy tính có internet, cài Zoom.
- Tài khoản Claude (khuyến nghị bản có phí).
- 1 đoạn mô tả sản phẩm/dịch vụ của bạn + vài review hoặc tin nhắn khách (không nhạy cảm).
- Chưa có dữ liệu thật? Dùng bộ mẫu thương hiệu Thảo An trong thư mục `04-demo-data/`.

## Đội AI Agent (bức tranh tổng)
1. Discovery Agent — hiểu khách, đặt câu hỏi đúng.
2. Customer Insight Agent — đọc dữ liệu ra insight có bằng chứng.
3. Content Engine Agent — biến insight thành nội dung đa kênh.
4. Outbound / Sales Agent — chấm điểm lead, cá nhân hóa tiếp cận.
5. Proposal Agent — soạn báo giá, proposal.
6. Closer & Automation — xử lý từ chối, chốt, tự động hóa.

## Thực hành: 2 agent bạn tự dựng

### Agent 1 — Discovery Agent
- Mở prompt: `03-prompts/01-discovery-agent.md`, copy vào Claude Project của bạn.
- Dán mô tả sản phẩm của bạn (hoặc `04-demo-data/san-pham-thao-an.md`).
- Kết quả: bối cảnh khách + 8-10 câu hỏi SPIN + 3 nỗi đau ưu tiên.

### Agent 2 — Customer Insight Agent
- Mở prompt: `03-prompts/02-customer-insight-agent.md`, copy vào Claude Project.
- Dán review/tin nhắn khách của bạn (hoặc `04-demo-data/reviews-khach-hang.md`).
- Kết quả: 5 insight có bằng chứng + góc nội dung + 1 bài social mẫu.

## Nguyên tắc dùng AI an toàn
- Chỉ để AI dùng dữ liệu bạn cung cấp, không để nó bịa.
- Yêu cầu AI dẫn bằng chứng và phân biệt điều khách nói với điều AI suy luận.
- Luôn tự duyệt trước khi gửi khách.

## Sau workshop
- Bạn có 2 agent chạy được ngay. Muốn xây trọn đội 6 agent + tự động hóa: xem khóa live 6 buổi (khai giảng 22/07).
