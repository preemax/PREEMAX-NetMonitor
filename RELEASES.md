# Release policy

نسخه‌های عمومی PREEMAX NetMonitor از طریق **GitHub Releases** منتشر می‌شوند.

## Version tags

- Release Candidate: `v1.0.0-rc44`
- Stable: `v1.0.0`

## Windows assets

نام‌گذاری استاندارد فایل‌های Windows:

- `PREEMAX_NetMonitor_Setup_<version>_win-x64.exe`
- `PREEMAX_NetMonitor_Portable_<version>_win-x64.zip`
- `SHA256SUMS.txt`
- `RELEASE_MANIFEST.json`

در صورت انتشار معماری ARM64:

- `PREEMAX_NetMonitor_Setup_<version>_win-arm64.exe`
- `PREEMAX_NetMonitor_Portable_<version>_win-arm64.zip`

## Android

برای Android، صفحه Release می‌تواند لینک انتشار رسمی مارکت‌ها را نمایش دهد. فایل APK فقط در صورت تصمیم ناشر برای توزیع مستقیم در GitHub قرار می‌گیرد.

## Release notes

هر Release باید حداقل شامل این موارد باشد:

- شماره نسخه
- پلتفرم و معماری
- تغییرات اصلی
- اصلاحات مهم
- محدودیت‌های شناخته‌شده در صورت وجود
- وضعیت امضای دیجیتال
- SHA‑256 فایل‌های منتشرشده

## Compatibility

Windows builds فعلی برای Windows 10/11 x64 منتشر می‌شوند مگر اینکه در Release مربوطه خلاف آن ذکر شده باشد.
