# تیزتر

انگلیسی |[چینی ساده شده](./README-zh_CN.md)

تروجان را با استفاده از رویکرد بدون سرور اجرا کنید

## شروع سریع

-   یک Worker جدید در داشبورد Cloudflare Workers ایجاد کنید.
-   کد را از[worker.js](./src/worker.js)به ویرایشگر کد کارگر
-   جایگزین کردن`sha224Password`با رمز عبور خودتان می توانید تولید کنید[اینجا](https://www.atatus.com/tools/sha224-to-hash). از طرف دیگر، می توانید اضافه کنید`SHA224PASS` environment variable in Cloudflare Workers settings later.
-   اتصال یک دامنه سفارشی به کارگر.
-   بازدید کنید`https://[YOUR_DOMAIN]/link`و جایگزین کنید`ca110us`با رمز عبور ساده شما

## پشتیبانی نشده

-   UDP 🙅 (زمان اجرا Cloudflare Workers هنوز از UDP پشتیبانی نمی کند)

## سلب مسئولیت

این پروژه فقط برای اهداف مطالعه/تحقیق است. کاربران مسئول رعایت قوانین و رفتار اخلاقی هستند. نویسنده مسئولیت سوء استفاده را از خود سلب می کند.

## ارجاع

[zizifn/edgetunnel](https://github.com/zizifn/edgetunnel)
