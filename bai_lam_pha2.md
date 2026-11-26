# BÀI LÀM PHA 2 – HACKATHON 02

- **Mã đề:** 07
- **Họ tên:** Nguyễn Xuân Cường
- **Lớp:**  CNTT1
- **Link repository Pha2:** https://github.com/Nguyen-Xuan-Cuong/HN-K26-CNTT1_PromptAI_H02_Pha1-Pha2
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):** ChatGPT

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đặt vé vào cổng ra JSON

**KET QUA AI**

```text
[
  {
    "loai_ve": "VEBUOICHIEU",
    "ngay_choi": "2026-12-20",
    "nguoi_lon": 2,
    "tre_em": 1,
    "loai_tu": "nho",
    "ghi_chu": null
  },
  {
    "loai_ve": "VECN",
    "ngay_choi": "2027-01-03",
    "nguoi_lon": 3,
    "tre_em": 0,
    "loai_tu": null,
    "ghi_chu": "1 người đang bó bột tay"
  },
  {
    "loai_ve": "VEVIP",
    "ngay_choi": null,
    "nguoi_lon": 4,
    "tre_em": 0,
    "loai_tu": "lon",
    "ghi_chu": "1 bạn đi xe lăn"
  }
]
```

**Link trò chuyện:** https://chatgpt.com/c/6b07e4a5-20f4-83ec-880b-cb8d1e7dfa76

## 4.3. Báo giá bằng Chain-of-Thought

**KET QUA AI**

```text
BÁO CÁO BÁO GIÁ VÉ ĐOÀN
1. Tiền vé người lớn

8 người lớn × 250.000 = 2.000.000 đồng

2. Tiền vé trẻ em

4 trẻ em (từ 1 m đến 1,4 m), mỗi vé bằng 60% vé người lớn:

250.000 × 60% = 150.000 đồng/vé

4 × 150.000 = 600.000 đồng

2 bé dưới 1 m: miễn phí = 0 đồng

3. Tổng tiền vé

2.000.000 + 600.000 + 0 = 2.600.000 đồng

4. Giảm giá đoàn

Đoàn có 8 người lớn nên được giảm 10%:

2.600.000 × 10% = 260.000 đồng

2.600.000 − 260.000 = 2.340.000 đồng

5. Phụ thu thuê áo phao

6 × 40.000 = 240.000 đồng

6. Tổng tiền

2.340.000 + 240.000 = 2.580.000 đồng

[RESULT: 2.580.000 đồng]
```

**Link trò chuyện:** https://chatgpt.com/c/6b07e4de-17dc-83ec-8c11-d45913db8ad4

### b) Kiểm tra kết quả AI

Đúng

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{"loai_su_co":"dong_khu_choi","so_khach":4,"so_khu_bi_dong":2,"tom_tat":"Hai khu trò chơi đóng cả ngày không báo trước, ảnh hưởng 4 khách mua vé cả ngày."}
```

**Link trò chuyện:** https://chatgpt.com/c/6b07e546-4d7c-83ec-a582-cc2b6e8c418f

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
Tiêu chí	Điểm	Minh chứng	Đề xuất sửa
Đúng thông tin (50%)	0/5	Giá vé chiều báo 150.000đ, sai giá chuẩn 180.000đ. Chính sách hoàn tiền mặt 100% sai quy định công ty.	Báo đúng giá 180.000đ và chính sách tặng vé nếu đóng cửa dưới 2 giờ; từ 2 giờ trở lên không bù.
Đầy đủ (30%)	1/3	Có đề cập giá vé và chính sách thời tiết nhưng thông tin sai; chưa hỏi ngày chơi, số vé để hỗ trợ đặt vé.	Trả lời chính xác cả hai nội dung và mời khách cung cấp ngày chơi, số vé.
Giọng điệu (20%)	1/2	Có lời chào lịch sự nhưng "mát rượi luôn", "ới em nhé" mang tính suồng sã.	Sử dụng ngôn ngữ lịch sự, chuyên nghiệp, phù hợp tư vấn khách hàng.
Tổng điểm	2/10		
```

**Link trò chuyện:** https://chatgpt.com/c/6b07e587-a158-83ec-b3b9-749c8caf389c
