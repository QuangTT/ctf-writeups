# PortSwigger Web Security Academy — Writeups

> Mỗi lab = 1 thư mục: `NN-ten-lab-slug/` chứa `writeup.md` + `assets/` + script khai thác (nếu có).

## Cấu trúc chuẩn

```
Portswigger/
├── README.md                  <- file này (index + checklist)
├── TEMPLATE-writeup.md        <- mẫu copy cho mỗi lab mới
├── <Topic>/                   <- ví dụ: SQL-Injection, Authentication, XSS...
│   ├── README.md              <- checklist labs của topic đó
│   └── NN-ten-lab/            <- ví dụ: 01-username-enumeration-via-different-responses/
│       ├── writeup.md
│       ├── assets/            <- ảnh, request/response, video
│       ├── exploit.py         <- (optional)
│       └── payloads.txt       <- (optional)
```

## Quy tắc đặt tên

- Topic: `Pascal-Case-Với-Gạch-Ngang` (VD: `SQL-Injection`, `Authentication`)
- Lab: `NN-slug-tienda` — `NN` là số thứ tự 2 chữ số, slug copy từ tên lab PortSwigger viết thường, gạch ngang. VD: `01-username-enumeration-via-different-responses`
- Ảnh: để trong `assets/`, đặt tên `01-burp-request.png`, `02-exploit.png`...
- Trong `writeup.md` link ảnh dạng tương đối: `![burp](./assets/01-burp-request.png)`

## Index Topics

| # | Topic | Thư mục | Status |
|---|-------|---------|--------|
| 01 | SQL Injection | `SQL-Injection/` | [ ] |
| 02 | NoSQL Injection | `NoSQL-Injection/` | [ ] |
| 03 | Cross-Site Scripting (XSS) | `Cross-Site-Scripting-XSS/` | [ ] |
| 04 | Cross-Site Request Forgery (CSRF) | `CSRF/` | [ ] |
| 05 | Clickjacking | `Clickjacking/` | [ ] |
| 06 | DOM-Based Vulnerabilities | `DOM-Based-Vulnerabilities/` | [ ] |
| 07 | Cross-Origin Resource Sharing (CORS) | `CORS/` | [ ] |
| 08 | XXE Injection | `XXE-Injection/` | [ ] |
| 09 | Server-Side Request Forgery (SSRF) | `SSRF/` | [ ] |
| 10 | HTTP Request Smuggling | `HTTP-Request-Smuggling/` | [ ] |
| 11 | OS Command Injection | `OS-Command-Injection/` | [ ] |
| 12 | Server-Side Template Injection (SSTI) | `SSTI/` | [ ] |
| 13 | Path Traversal | `Path-Traversal/` | [ ] |
| 14 | Access Control | `Access-Control/` | [ ] |
| 15 | Authentication | `Authentication/` | [x] đang làm |
| 16 | WebSockets | `WebSockets/` | [ ] |
| 17 | Web Cache Poisoning | `Web-Cache-Poisoning/` | [ ] |
| 18 | Insecure Deserialization | `Insecure-Deserialization/` | [ ] |
| 19 | Information Disclosure | `Information-Disclosure/` | [ ] |
| 20 | Business Logic Vulnerabilities | `Business-Logic-Vulnerabilities/` | [ ] |
| 21 | HTTP Host Header Attacks | `Host-Header-Attacks/` | [ ] |
| 22 | OAuth Authentication | `OAuth-Authentication/` | [ ] |
| 23 | File Upload Vulnerabilities | `File-Upload-Vulnerabilities/` | [ ] |
| 24 | JWT Attacks | `JWT-Attacks/` | [ ] |
| 25 | Prototype Pollution | `Prototype-Pollution/` | [ ] |
| 26 | GraphQL API | `GraphQL-API/` | [ ] |
| 27 | API Testing | `API-Testing/` | [ ] |
| 28 | LLM Attacks | `LLM-Attacks/` | [ ] |
| 29 | Race Conditions | `Race-Conditions/` | [ ] |
| 30 | Essential Skills | `Essential-Skills/` | [ ] |

## Cách thêm lab mới (ví dụ Authentication lab 02)

```bash
# 1. tạo thư mục từ repo root
mkdir -p "Portswigger/Authentication/02-username-enumeration-via-account-lock/assets"

# 2. copy template
cp Portswigger/TEMPLATE-writeup.md "Portswigger/Authentication/02-username-enumeration-via-account-lock/writeup.md"

# 3. sửa writeup.md, thêm ảnh vào assets/, rồi tick checklist trong Portswigger/Authentication/README.md
```

## Lab đã làm

- [x] Authentication / 01-username-enumeration-via-different-responses
