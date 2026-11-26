# BÀI LÀM PHA 2 – HACKATHON 02

- **Mã đề:** 07
- **Họ tên:** Hà Gia Bách
- **Lớp:** CNTT2
- **Link repository Pha2:**
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):** CLAUDE

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đặt vé vào cổng ra JSON

**KET QUA AI**

```text
(Dán câu trả lời của AI vào đây (bấm nút Copy dưới câu trả lời) – xoá dòng này)
[
{"loai_ve": "VECH", "ngay_choi": "2026-12-20", "nguoi_lon": 2, "tre_em": 1, "loai_tu": "nho", "ghi_chu": null},
{"loai_ve": "VECN", "ngay_choi": "2027-01-03", "nguoi_lon": 3, "tre_em": 0, "loai_tu": null, "ghi_chu": "1 người đang bó bột tay"},
{"loai_ve": "VEVIP", "ngay_choi": null, "nguoi_lon": 4, "tre_em": 0, "loai_tu": "lon", "ghi_chu": "1 bạn đi xe lăn"}
]
```

**Link trò chuyện:** https://claude.ai/share/216f0929-cca3-4122-bc34-c0a40e8ee9cc

## 4.3. Báo giá bằng Chain-of-Thought

**KET QUA AI**

```text
(Dán câu trả lời của AI vào đây (bấm nút Copy dưới câu trả lời) – xoá dòng này)
Bước 1: Tính vé người lớn

Giá vé VECN: 250.000 đồng/vé
Số người lớn: 8
8 × 250.000 = 2.000.000 đồng

Bước 2: Tính vé trẻ em (đối chiếu quy tắc 1)

1,05 m nằm trong khoảng 1 m đến 1,4 m, tính 60% giá
1,15 m nằm trong khoảng 1 m đến 1,4 m, tính 60% giá
1,2 m nằm trong khoảng 1 m đến 1,4 m, tính 60% giá
1,3 m nằm trong khoảng 1 m đến 1,4 m, tính 60% giá
2 bé cao dưới 1 m: miễn phí, 2 × 0 = 0 đồng
Giá vé 1 trẻ em: 250.000 × 60% = 150.000 đồng
Tiền vé trẻ em: 4 × 150.000 = 600.000 đồng
Tổng tiền vé trước giảm: 2.000.000 + 600.000 = 2.600.000 đồng

Bước 3: Đối chiếu ưu đãi giảm giá (quy tắc 2)

Điều kiện: đoàn từ 8 người lớn trở lên. Đoàn có đúng 8 người lớn, nên đủ điều kiện giảm.
Giảm 10% trên tiền vé (người lớn + trẻ em): 2.600.000 × 10% = 260.000 đồng
Tiền vé sau giảm: 2.600.000 − 260.000 = 2.340.000 đồng

Bước 4: Tính phụ thu thuê áo phao (quy tắc 3)

Phụ thu: 40.000 đồng/chiếc, không được giảm giá
Số áo phao: 6
6 × 40.000 = 240.000 đồng

Bước 5: Tính tổng tiền (quy tắc 4)

Tổng tiền = tiền vé sau giảm + phụ thu
2.340.000 + 240.000 = 2.580.000 đồng

[RESULT: 2.580.000 đồng]
```

**Link trò chuyện:** https://claude.ai/share/3ff3de8f-4e05-4e51-b613-bf6c89d88385

### b) Kiểm tra kết quả AI

(Ghi kết luận AI đúng hay sai; nếu sai, ghi bước sai đầu tiên và kết quả đúng của bước đó – xoá dòng này)

KẾT QUẢ ĐÚNG

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
(Dán câu trả lời của AI vào đây (bấm nút Copy dưới câu trả lời) – xoá dòng này)

{"loai_su_co": "dong_khu_choi", "so_khach": 4, "so_khu_bi_dong": 2, "tom_tat": "Hai khu trượt nước chính và sóng nhân tạo đóng cả ngày, website không báo trước."}
```

**Link trò chuyện:** https://claude.ai/share/a4115e2a-4c7f-4861-af89-6c4ab11b7b71

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
(Dán câu trả lời của AI vào đây (bấm nút Copy dưới câu trả lời) – xoá dòng này)


```
![alt text](image.png)

**Link trò chuyện:** https://claude.ai/share/dae49c5c-d7df-4a1d-8fa2-ce4e839bee4b
