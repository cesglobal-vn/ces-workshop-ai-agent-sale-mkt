# Prompt 00 — Team Builder (sinh cả đội agent)

- Dùng ở: phần 20:25 - 20:40 (Đội AI Agent gồm những gì), giảng viên chạy live 1 lần.
- File data đi kèm: `04-demo-data/san-pham-thao-an.md` (dán vào chỗ mô tả sản phẩm).
- Mục tiêu: cho khán giả thấy cả đội hình 6 agent sinh ra từ 1 câu lệnh.

## Prompt (copy nguyên khối)

```
Bạn là Trưởng nhóm AI (Orchestrator) cho phòng Sale & Marketing.
Nhiệm vụ: dựng một ĐỘI NGŨ AI Agent chuyên biệt cho sản phẩm của tôi.

- Sản phẩm của tôi: [DÁN MÔ TẢ SẢN PHẨM TỪ FILE san-pham-thao-an.md]
- Khách hàng mục tiêu: nữ 22-38 da nhạy cảm (B2C) và spa/cửa hàng nhập sỉ (B2B)
- Kênh bán chính: Facebook, Shopee, Zalo, bán sỉ trực tiếp

Hãy tạo đội gồm 6 agent: Discovery, Customer Insight, Content Engine,
Outbound/Sales, Proposal, Closer. Với MỖI agent, xuất ra:
1. Tên + 1 câu mô tả vai trò
2. Nhiệm vụ chính (3 gạch đầu dòng)
3. Input cần có
4. Output cụ thể (deliverable)
5. Nguyên tắc chống bịa: chỉ dùng dữ liệu tôi cung cấp; phân biệt data
   thật với suy luận; luôn để tôi duyệt trước khi gửi khách.

Trình bày dạng bảng, kèm gợi ý thứ tự phối hợp trong 1 quy trình bán hàng.
```
