# Veksa-self-free-edition





<!-- README.md -->

<div align="center" style="font-family: Arial; padding: 20px;">

<h1 style="color:#3a3a3a;">🤖 Telegram SelfBot</h1>
<p style="font-size: 18px;">ابزاری پیشرفته برای اتوماسیون، شخصی‌سازی و مدیریت حرفه‌ای اکانت تلگرام شخصی</p>

<img src="https://img.shields.io/badge/Python-3.9+-blue.svg" />
<img src="https://img.shields.io/badge/Telethon-1.28+-green.svg" />
<img src="https://img.shields.io/badge/Status-Active-success.svg" />

<hr style="border: 1px solid #ccc;" />

<h2>📌 امکانات اصلی</h2>
<ul align="right" dir="rtl" style="text-align: right;">
  <li>✅ بروزرسانی خودکار نام، بیو، و عکس پروفایل با ساعت ایران</li>
  <li>💬 پاسخ به پیام‌ها، مدیریت دشمن‌ها و پیام‌های خاص</li>
  <li>🎲 بازی دایس (با انتخاب عدد)</li>
  <li>💻 مدیریت کامل با فایل JSON و تنظیمات پویا</li>
  <li>🎭 ارسال واکنش به پیام‌ها و اجرای خودکار اکشن‌های تایپ، بازی، صدا و ویدیو</li>
  <li>🧠 حافظه و پردازشگر قابل مانیتور با دستور help</li>
</ul>

<hr style="border: 1px solid #ccc;" />

<h2>🧩 وابستگی‌ها</h2>

<p>برای اجرای این پروژه، کتابخانه‌های زیر باید نصب شوند:</p>

```bash
pip install telethon psutil asyncio aiocron pytz googletrans==4.0.0-rc1 gtts requests
<hr style="border: 1px solid #ccc;" /> <h2>⚙️ نحوه اجرا</h2> <ol align="right" dir="rtl" style="text-align: right;"> <li>📁 فایل را clone یا دانلود کن</li> <li>🔑 API ID و API HASH خودت را در کد جایگزین کن</li> <li>🟢 ترمینال را باز کن و دستور زیر را بزن: <pre><code>python main.py</code></pre> </li> <li>🔐 اولین بار، اطلاعات ورود شما درخواست می‌شود (session ذخیره می‌شود)</li> </ol> <hr style="border: 1px solid #ccc;" /> <h2>📚 ساختار فایل data.json</h2>
json
Copy
Edit
{
  "timename": "on",
  "timebio": "off",
  "timeprof": "off",
  "bot": "on",
  "hashtag": "off",
  "bold": "off",
  ...
}
<hr style="border: 1px solid #ccc;" /> <h2>📎 دستورات پرکاربرد</h2>
text
Copy
Edit
.timebio on|off         → فعال‌سازی بیو زمان‌دار
.timename on|off        → تغییر نام زمان‌دار
.timeprof on|off        → تغییر پروفایل با زمان
.comment on|off         → پاسخ خودکار به پیام فوروارد شده
.commentText متن        → تعیین متن پاسخ
.addenemy id            → افزودن دشمن
.listenemy              → نمایش لیست دشمن‌ها
.reaction متن           → واکنش خاص به پیام‌ها
.dice 3                 → بازی دایس با عدد انتخابی
.help                   → نمایش وضعیت بات و تنظیمات
<hr style="border: 1px solid #ccc;" /> <h2>📷 پیش‌نمایش</h2> <img src="https://telegra.ph/file/1b5a45ab4e49d1706e523.jpg" alt="screenshot" style="border-radius: 12px; box-shadow: 0 0 10px #ccc; width: 70%;"/> <hr style="border: 1px solid #ccc;" /> <h2>👨‍💻 توسعه‌دهنده</h2> <p>این پروژه توسط <b>Mahdi Najari</b> توسعه داده شده است.</p> <p>📫 ارتباط با من در <a href="https://linkedin.com/in/mahdi-najari" target="_blank">LinkedIn</a></p> </div> ```
