# KengStreamio — Android App Releases

![Version](https://img.shields.io/badge/version-1.55.1-blue)
![Platform](https://img.shields.io/badge/platform-Android%20TV%20%7C%20Phone-green)
![License](https://img.shields.io/badge/license-Private-red)

Trang phân phối APK chính thức của **KengStreamio** — ứng dụng xem phim cho Android TV và điện thoại Android.

---

## ⬇️ Latest Release

**[Download KengStreamio v1.55.1](https://github.com/kengstreamio/KengStreamio-Apps/releases/download/v1.55.1/kengstreamio-v1.55.1-arm64-v8a.apk)**  
Version: `1.55.1` (build 58) · Size: ~82.8 MB · 2026-06-21

> • Fix crash khi chuyển server từ ExoPlayer sang WebView/JWPlayer
> • Giữ nguyên server index khi đổi tập hoặc play next
> • Hỗ trợ chọn chất lượng sub-server, fix auto-click embed, D-pad TV

---

## 📱 Yêu Cầu Hệ Thống

| Thiết bị | Yêu cầu |
|----------|---------|
| Android TV | Android 7.0+ (API 24+), D-pad remote |
| Android Phone | Android 7.0+ (API 24+) |
| RAM | Tối thiểu 2GB |
| Storage | ~50MB |

---

## 🔧 Cài Đặt

1. Tải APK từ link **Latest Release** ở trên
2. Trên thiết bị: **Settings → Security → Unknown sources → Allow**
3. Mở file APK vừa tải → Install
4. Mở app KengStreamio

**Android TV (qua ADB):**
```bash
adb install -r kengstreamio-v1.0.0.apk
```

---

## 🔒 Bảo Mật

- APK được ký bằng keystore riêng (`kengstreamio_pro.jks`)
- Không thu thập dữ liệu cá nhân ngoài thông tin đăng nhập Google (tùy chọn)
- Firebase Crashlytics chỉ thu thập crash reports ẩn danh

---

## 📞 Liên Hệ

Báo lỗi hoặc góp ý: tạo Issue trong repo này.
