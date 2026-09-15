# Lab: <Tên lab PortSwigger>

- **Topic:** <VD: Authentication>
- **Level:** Apprentice / Practitioner / Expert
- **Link lab:** https://portswigger.net/web-security/<topic>/<lab-slug>
- **Status:** [x] Solved / [ ] Unsolved
- **Ngày:** YYYY-MM-DD

## 1. Mô tả / Mục tiêu

> Lab yêu cầu gì? Điều kiện solve là gì? (VD: login vào tài khoản victim, xóa user Carlos...)

## 2. Phân tích

- Điểm vào (endpoint, param, header...):
- Cơ chế lỗi:
- Tool dùng: Burp Repeater / Intruder / Decoder...

## 3. Các bước khai thác

### Bước 1 — Recon
```http
GET /... HTTP/2
Host: xxx.web-security-academy.net
...
```

### Bước 2 — Khai thác
Payload:
```
<paste payload>
```

Ảnh minh họa:
![step](./assets/01-burp-request.png)

### Bước 3 — Solve
Kết quả:

## 4. Payload / Script cuối

```python
# exploit.py (nếu có) — paste code ngắn gọn
import requests
```

Hoặc file riêng: `./exploit.py`, `./payloads.txt`

## 5. Mitigation (cách fix)

- ...
- ...

## 6. Tham khảo

- Link docs PortSwigger, cheat sheet...
