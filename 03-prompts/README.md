# Bản đồ Prompt và File data đi kèm

> Tra nhanh: prompt nào, dùng ở phút nào, đi với file data nào. Giảng viên mở đúng cặp file khi tới phần tương ứng.

| Prompt | Dùng ở phần | File data đi kèm | Đầu ra |
|---|---|---|---|
| `00-team-builder.md` | 20:25 - 20:40 (giới thiệu đội) | `04-demo-data/san-pham-thao-an.md` | Bảng 6 agent |
| `01-discovery-agent.md` | 21:05 - 21:45 (hands-on, agent 1) | `04-demo-data/san-pham-thao-an.md` | Câu hỏi SPIN + nỗi đau |
| `02-customer-insight-agent.md` | 21:05 - 21:45 (hands-on, agent 2) | `04-demo-data/reviews-khach-hang.md` | 5 insight + bài mẫu |
| `03-usecase-outbound-sales.md` | 20:40 - 21:05 (demo sống) | `04-demo-data/leads-b2b.csv` | Lead scoring + email |
| `04-usecase-content-engine.md` | 20:40 - 21:05 (demo sống) | `04-demo-data/insight-mau.md` | Lịch nội dung 14 ngày |

## Thứ tự đội chạy trong demo sống (20:40 - 21:05)
1. Discovery Agent (prompt 01) đọc `san-pham-thao-an.md` để map nhu cầu.
2. Customer Insight Agent (prompt 02) đọc `reviews-khach-hang.md` để ra insight.
3. Content Engine Agent (prompt 04) lấy `insight-mau.md` để dựng chiến dịch 14 ngày.
4. Outbound Agent (prompt 03) đọc `leads-b2b.csv` để chấm lead + viết email.

## Học viên tự làm (hands-on)
Chỉ dựng 2 agent: prompt 01 (Discovery) và prompt 02 (Customer Insight), trên sản phẩm của chính học viên. Ai chưa có sản phẩm thì dùng bộ data Thảo An trong `04-demo-data/`.
