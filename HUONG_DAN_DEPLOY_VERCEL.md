# 🚀 Hướng dẫn Deploy App Đặt Cơm lên Vercel

## ✅ Yêu cầu:
- Có tài khoản GitHub (miễn phí)
- Có tài khoản Vercel (miễn phí, dùng GitHub để login)
- File `app-dat-com-v2.html`

---

## 📋 Các bước thực hiện:

### **Bước 1: Tạo Repository trên GitHub**

1. Truy cập: https://github.com/new
2. Điền thông tin:
   - **Repository name:** `app-dat-com` (tên bất kỳ)
   - **Description:** "Ứng dụng đặt cơm cho công ty"
   - **Public** (công khai để mọi người truy cập)
   - ✅ Tick "Add a README file"
3. Click **"Create repository"**

✨ **Bạn vừa tạo repository xong!**

---

### **Bước 2: Sử dụng web-based editor (Cách dễ nhất)**

1. Vào repository vừa tạo
2. Click nút **"Add file"** → **"Create new file"**
3. Đặt tên file: `index.html`
4. Copy-paste toàn bộ code từ file `app-dat-com-v2.html` vào
5. Click **"Commit changes"** → **"Commit directly to the main branch"**

✨ **Bạn vừa upload file lên GitHub!**

---

### **Bước 3: Deploy lên Vercel**

1. Truy cập: https://vercel.com
2. Click **"Sign Up"** → Chọn **"Continue with GitHub"**
3. Authorize Vercel để truy cập GitHub
4. Sau khi login, click **"New Project"**
5. Chọn repository `app-dat-com` vừa tạo
6. Vercel sẽ tự nhận diện (vì là `index.html`)
7. Click **"Deploy"**

⏳ **Chờ khoảng 30-60 giây...**

✨ **Xong! Website của bạn đang chạy!**

---

### **Bước 4: Lấy URL website**

Sau khi deploy xong, Vercel sẽ cho bạn URL dạng:
```
https://app-dat-com.vercel.app
```

Hoặc bạn có thể đặt tên domain custom (miễn phí):
```
https://app-dat-com-company.vercel.app
```

---

## 🌐 **Chia sẻ với nhân viên:**

1. Gửi URL cho mọi người trong công ty
2. Họ có thể truy cập trên **bất kỳ thiết bị nào**: điện thoại, laptop, tablet
3. Họ có thể bắt đầu đặt cơm ngay!

---

## 📌 **Lưu ý quan trọng:**

### ⚠️ **Dữ liệu hiện tại (localStorage):**
- Mỗi người sẽ có dữ liệu **riêng** trên máy/điện thoại của họ
- Dữ liệu sẽ **mất** nếu:
  - Xóa cache/cookie trình duyệt
  - Dùng máy khác không có sẵn dữ liệu

### ✅ **Để toàn công ty xem chung dữ liệu:**
Cần setup Database + Backend (phức tạp hơn, mình giúp sau)

---

## 🔄 **Cập nhật code sau này:**

Nếu muốn sửa app:

1. Vào GitHub repository
2. Click vào file `index.html`
3. Click ✏️ **"Edit this file"**
4. Sửa code
5. Click **"Commit changes"**
6. Vercel **tự động deploy** ngay (không cần làm gì thêm!)

---

## 🚨 **Nếu có lỗi:**

**Lỗi 1: "Cannot GET /"**
- Kiểm tra tên file có phải `index.html` không?
- Phải in hoa/thường đúng!

**Lỗi 2: Website trắng không hiển thị gì**
- Mở DevTools (F12) → Tab Console
- Xem có error gì không?
- Báo cho mình fix!

**Lỗi 3: Không thể login GitHub**
- Kiểm tra tài khoản GitHub đúng chưa?
- Xóa cookie/cache thử lại

---

## 💡 **Tiếp theo (tùy chọn):**

Sau khi đã có website chạy trên Vercel, nếu bạn muốn:

### 1️⃣ **Toàn công ty xem chung dữ liệu:**
→ Cần setup Firebase + Backend API
→ Mình sẽ viết code giúp

### 2️⃣ **Admin dashboard để thống kê:**
→ Thêm trang admin để xem báo cáo
→ Export Excel, PDF

### 3️⃣ **Gửi email xác nhận đơn hàng:**
→ Khi nhân viên đặt xong → tự động gửi email

### 4️⃣ **Thanh toán online:**
→ Tích hợp Stripe, Momo, ZaloPay

---

## ✉️ **Cần giúp?**

Nếu gặp vấn đề:
1. Chụp màn hình error
2. Mô tả bước nào bị lỗi
3. Báo cho mình sẽ fix!

**Chúc bạn thành công! 🎉**
