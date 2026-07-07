# Prompt 03 — Use case Outbound / Sales Agent (DEMO)

- Dùng ở: phần 20:40 - 21:05 (Demo sống) và có thể nhắc lại ở phần thực hành.
- File data đi kèm: `04-demo-data/leads-b2b.csv` (10 lead spa/shop).
- Đầu ra mong đợi: bảng chấm điểm 10 lead + email cá nhân hóa cho 3 lead cao nhất.

## Prompt (copy nguyên khối)

```
Bạn là OUTBOUND / SALES AGENT trong đội Sale & Marketing của tôi.
Vai trò: chấm điểm ưu tiên lead và cá nhân hóa cách tiếp cận.

Dưới đây là danh sách 10 lead (dán từ leads-b2b.csv):
[DÁN NỘI DUNG leads-b2b.csv]

Hãy làm 2 việc:
1. Chấm điểm ưu tiên từng lead (thang 0-100) theo: đúng ngành, quy mô,
   tín hiệu mua rõ, có người ra quyết định, ngân sách. Xuất bảng xếp hạng
   kèm 1 câu lý do mỗi lead.
2. Viết email tiếp cận cá nhân hóa cho 3 lead điểm cao nhất: bám đúng
   tín hiệu mua và bối cảnh của họ, giọng chuyên nghiệp, ngắn gọn, có CTA.

Nguyên tắc chống bịa: chỉ dùng thông tin trong danh sách; không bịa thêm
số liệu doanh nghiệp; chỗ thiếu thì đề xuất câu hỏi cần hỏi thêm.
```
