# Slide workshop (đã hoàn thiện)

Bộ slide 16 trang cho workshop "Lập đội ngũ AI Agent cho Sale & Marketing".

- `Workshop_AI_Agent_Sale_Marketing.pptx` : file trình chiếu 16 slide (16:9), mỗi slide full-bleed.
- `slides/slide-01.png` đến `slide-16.png` : 16 ảnh slide.
- `noi-dung-slide.md` : nội dung text đầy đủ 16 slide (để chỉnh/sinh lại khi cần).

## Cách tạo (tham khảo, tái tạo được)
- Style: infographic, nền trắng, màu theo logo CES (teal #00A99D, navy #0B2349, đỏ #E03131, cam #F5A623), logo CES ref vào góc trái, text tiếng Việt có dấu.
- Công cụ: ima2-gen (GPT Image 2, OAuth free). Chạy `ima2 serve` rồi:
  `Get-Content -Raw -Encoding UTF8 prompt.txt | ima2 gen --stdin --provider oauth --ref <logo.png> --size 1792x1024 -q high -o slide.png`
- Prompt từng slide dựng từ `noi-dung-slide.md` (tiêu đề + gạch đầu dòng + mô tả visual).

## Chỉnh sửa
- Sửa text: mở PPTX chèn textbox đè, hoặc sinh lại ảnh slide đó từ prompt tương ứng.
- Muốn đổi nội dung: sửa `noi-dung-slide.md` rồi sinh lại slide liên quan.
