# Kịch bản giảng dạy chi tiết (facilitator script)

> Mục tiêu: bất kỳ giảng viên nào mở file này cũng dạy được đúng chương trình. Mỗi phần ghi rõ: nói gì, làm gì, mở file nào, đầu ra mong đợi, lỗi thường gặp.
> Tổng: 150 phút, online Zoom. Cần 1 giảng viên chính + 1 trợ giảng trực chat.

## Trước buổi (xem thêm `checklist-truoc-buoi.md`)
- Mở sẵn: slide, 1 cửa sổ Claude đã đăng nhập, thư mục `04-demo-data/` và `03-prompts/`.
- Gửi học viên trước: link Zoom, `02-hoc-vien/huong-dan-chuan-bi-truoc-buoi.md`, 3 prompt hands-on.

---

## Phần 1 — Mở màn + Hook (20:00 - 20:10)
- NÓI: chào, giới thiệu bản thân + CES Global trong 1 phút. Nêu 1 con số về ngân sách ads/content mà lead vẫn rời rạc.
- LÀM: hỏi nhanh qua chat "Ai đang dùng AI cho content hoặc sale mỗi ngày, gõ 1". Trợ giảng đếm nhanh.
- CHỐT: "Hôm nay ta không học thêm prompt, ta học cách lập một ĐỘI agent."

## Phần 2 — Vì sao AI Sale-MKT chưa ra kết quả (20:10 - 20:25)
- NÓI: thông điệp lõi. AI rời rạc vì mỗi người 1 kiểu, không có hệ thống chung.
- LÀM: chiếu slide bảng trước/sau (AI rời rạc vs đội AI Agent dùng chung dữ liệu, brand voice, có log).
- CHỐT: giải pháp là lập một đội agent như phòng Sale-MKT thu nhỏ.

## Phần 3 — Đội AI Agent gồm những gì (20:25 - 20:40)
- NÓI: giới thiệu 7 vai trò (xem bảng trong `00-chuong-trinh/chuong-trinh-workshop.md`).
- LÀM (demo live): mở `03-prompts/00-team-builder.md`, copy prompt, dán mô tả sản phẩm từ `04-demo-data/san-pham-thao-an.md`, chạy trên Claude. Chiếu cho khán giả thấy đội 6 agent sinh ra.
- ĐẦU RA MONG ĐỢI: 1 bảng 6 agent có vai trò + đầu ra.
- LỖI THƯỜNG GẶP: nếu Claude trả lời dài dòng, nhấn "trình bày dạng bảng" lại.

## Phần 4 — Demo sống: cả đội chạy 1 mục tiêu (20:40 - 21:05)
- NÓI: "Giờ ta giao cho đội 1 mục tiêu thật và xem chúng phối hợp."
- LÀM theo thứ tự (xem `03-prompts/README.md`):
  1. Discovery Agent (prompt 01) đọc `san-pham-thao-an.md`: ra câu hỏi + nỗi đau.
  2. Customer Insight Agent (prompt 02) đọc `reviews-khach-hang.md`: ra 5 insight có bằng chứng.
  3. Content Engine (prompt 04) lấy `insight-mau.md`: ra lịch 14 ngày.
  4. Outbound Agent (prompt 03) đọc `leads-b2b.csv`: chấm điểm 10 lead + email cho 3 lead top.
- NHẤN: mỗi bước dừng 20 giây chỉ ra chỗ agent DẪN BẰNG CHỨNG, không bịa; nhắc luôn có người duyệt trước khi gửi.
- ĐẦU RA MONG ĐỢI: khán giả thấy 1 chuỗi insight -> nội dung -> email liền mạch.

## Phần 5 — Thực hành: học viên tự dựng 2 agent (21:05 - 21:45)
- Cách chạy: giảng viên làm mẫu 1 bước, cho 5-7 phút để học viên tự làm, trợ giảng trực chat gỡ vướng.
- BƯỚC 1 (5'): mỗi người tạo 1 Claude Project cho sản phẩm của mình. Chưa có sản phẩm thì dùng data Thảo An.
- BƯỚC 2 (15'): dựng Discovery Agent bằng `03-prompts/01-discovery-agent.md`. Học viên dán mô tả sản phẩm, chạy, dán kết quả vào chat.
- BƯỚC 3 (18'): dựng Customer Insight Agent bằng `03-prompts/02-customer-insight-agent.md`, dán review (của mình hoặc `reviews-khach-hang.md`), nhận 5 insight + 1 bài.
- ĐẦU RA MONG ĐỢI: mỗi học viên có 2 agent chạy được.
- LỖI THƯỜNG GẶP: (a) chưa đăng nhập Claude, trợ giảng xử lý riêng; (b) dán thiếu data, agent hỏi lại là đúng, nhắc học viên bổ sung; (c) agent bịa, chỉ ra và yêu cầu thêm "chỉ dùng dữ liệu tôi cung cấp".

## Phần 6 — Bức tranh lớn: 6 buổi (21:45 - 21:55)
- NÓI: workshop mới chạm 2/7 agent. Khóa live 6 buổi xây trọn đội + Automation + đóng gói Skill/Playbook.
- LÀM: chiếu slide ánh xạ 6 buổi.

## Phần 7 — Chốt: Ưu đãi & CTA (21:55 - 22:08)
- NÓI: giới thiệu khóa live KG 22/07 + ưu đãi riêng người dự (giới hạn) + bộ tài liệu 99k.
- LÀM: hiện QR/form đăng ký. Trợ giảng thả link vào chat.

## Phần 8 — Q&A + đăng ký (22:08 - 22:30)
- LÀM: trả lời câu hỏi. Hướng dẫn để lại SĐT nhận bộ prompt. Người quan tâm khóa để lại SĐT nhận tư vấn 1-1.
- KẾT: cảm ơn, nhắc mốc khai giảng 22/07.

---

## Nguyên tắc xuyên suốt (nhắc lại nhiều lần)
- Chống bịa: AI chỉ dùng dữ liệu được cung cấp, dẫn bằng chứng, phân biệt data thật vs suy luận.
- Human review: luôn có người duyệt trước khi gửi khách.
- Làm tới đâu xem kết quả tới đó, không lý thuyết suông.
