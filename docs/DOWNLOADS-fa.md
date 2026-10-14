# دانلود و به‌روزرسانی آزادبرد

نسخهٔ جدید عمومی: **[۱٫۳٫۱۰ — آزمایشی](https://github.com/TIR3D4/AzadBird/releases/tag/v1.3.10)**. بررسی نهایی عملکرد و همهٔ سناریوهای شبکه هنوز کامل نیست.

## انتخاب فایل

| فایل | مناسب برای | حجم |
|---|---|---:|
| [Android · ARM64](https://github.com/TIR3D4/AzadBird/releases/download/v1.3.10/AzadBird-Android-arm64.apk) | بیشتر گوشی‌های جدید؛ از جمله Redmi 13 | ۴۳٫۴۵ MiB |
| [Android · Universal](https://github.com/TIR3D4/AzadBird/releases/download/v1.3.10/AzadBird-Android-universal.apk) | معماری نامشخص؛ شامل ARM64، ARMv7، x86 و x86_64 | ۱۴۶٫۷۷ MiB |

فقط یکی از این دو APK را نصب کنید. هر دو نسخهٔ ۱٫۳٫۱۰ با امکانات یکسان‌اند و به اندروید ۷ یا جدیدتر نیاز دارند. نسخهٔ iOS یا دسکتاپ در این انتشار وجود ندارد.

فایل‌های **Source code (zip/tar.gz)** را برای نصب دانلود نکنید؛ GitHub آن‌ها را از مستندات همین مخزن تولید می‌کند و APK نیستند.

## نصب و به‌روزرسانی

۱. APK را از لینک‌های بالا یا [Releases رسمی](https://github.com/TIR3D4/AzadBird/releases) دریافت و باز کنید.

۲. اگر اندروید درخواست کرد، اجازهٔ نصب را فقط برای همان مرورگر یا مدیر فایل فعال کنید.

۳. نسخهٔ جدید را روی اپ موجود نصب کنید؛ حذف اپ یا پاک‌کردن داده‌ها لازم نیست و ممکن است اشتراک‌های ذخیره‌شده را از بین ببرد.

۴. برنامه را باز کنید و از اشتراک موجود استفاده کنید یا لینک خودتان را اضافه کنید. هنگام نخستین اتصال، درخواست VPN اندروید را بررسی و تأیید کنید.

اگر ناسازگاری امضا یا خطای نصب دیدید، برنامه را حذف نکنید و به [پشتیبانی](https://t.me/AzadBirdnet) پیام بدهید. اندروید معمولاً نصب نسخهٔ قدیمی‌تر روی نسخهٔ جدید را قبول نمی‌کند.

## بررسی فایل

[SHA256SUMS.txt نسخهٔ ۱٫۳٫۱۰](https://github.com/TIR3D4/AzadBird/releases/download/v1.3.10/SHA256SUMS.txt) شامل هش هر دو APK است.

در PowerShell ویندوز:

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath .\AzadBird-Android-arm64.apk
```

در Linux:

```sh
sha256sum AzadBird-Android-arm64.apk
```

خروجی را با سطر نام همان فایل در SHA256SUMS مقایسه کنید. این بررسی تغییر یا خرابی فایل را تشخیص می‌دهد؛ جای بررسی امضای APK توسط اندروید را نمی‌گیرد.

<details>
<summary>اطلاعات فنی امضا و بسته</summary>

شناسهٔ اپ: `app.azadbird.android`

نسخهٔ ۱٫۳٫۱۰، کد نسخهٔ ۱۴۰. هر دو APK با هویت امضای قبلی برنامه ساخته شده‌اند.

اثر انگشت SHA-256 گواهی امضا:

```text
a91795d2840378ed112d3bb9e27048b366f416f27b7d8782d80bcdf352c5a23c
```

با Android SDK Build Tools می‌توانید امضا را بررسی کنید:

```sh
apksigner verify --verbose --print-certs AzadBird-Android-arm64.apk
```

[مشخصات دقیق بسته‌ها](https://github.com/TIR3D4/AzadBird/releases/download/v1.3.10/release-manifest.json) · [اعلان‌های کتابخانه‌های ثالث](https://github.com/TIR3D4/AzadBird/releases/download/v1.3.10/THIRD-PARTY-NOTICES.txt)

</details>

## نسخه‌های قبلی

[۱٫۳٫۹](https://github.com/TIR3D4/AzadBird/releases/tag/v1.3.9) · [۱٫۳٫۸](https://github.com/TIR3D4/AzadBird/releases/tag/v1.3.8) · [تمام انتشارها](https://github.com/TIR3D4/AzadBird/releases)

همهٔ نسخه‌های فعلی با برچسب **Pre-release** منتشر شده‌اند. فایل‌های یادداشت و manifest همراه آن‌ها، سوابق زمان ساخت‌اند؛ توضیحات صفحهٔ Release وضعیت جاری انتشار را بیان می‌کند. از حذف اطلاعات برای اجبار به بازگشت نسخه خودداری کنید.
