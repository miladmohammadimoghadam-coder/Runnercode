# Runnercode (رانرکد)

🌐 [runnercode.ir](https://runnercode.ir)

[فارسی](#فارسی) · [English](#english)

---

<a id="فارسی"></a>

<div dir="rtl">

## فارسی

**ویرایشگر آنلاین و رایگان برای نوشتن، اجرا و پیش‌نمایش زنده‌ی کد HTML، CSS و JavaScript؛ در یک صفحه، بدون نصب و بدون حساب کاربری.**

### این پروژه چیه؟

Runnercode یه جایگزین سبک و فارسی برای CodePen و JSFiddle هست. کدت رو یه طرف می‌نویسی و نتیجه رو همون لحظه طرف دیگه می‌بینی. همه‌چیز توی مرورگر خودت اجرا می‌شه و چیزی روی سرور آپلود نمی‌شه.

### امکانات

- **پیش‌نمایش زنده:** نتیجه موقع تایپ خودکار به‌روز می‌شه.
- **کار در یک فایل:** HTML و CSS و JavaScript رو با هم توی یک `index.html` می‌نویسی.
- **تشخیص خطا:** تگ بسته‌نشده، `id` تکراری، خطای نوشتاری جاوااسکریپت و آکولاد ناقص CSS داخل خود ادیتور علامت می‌خورن و نوار پایین اولین مشکل رو نشون می‌ده.
- **آپلود و دانلود:** فایل `.html`، `.htm` یا `.txt` رو باز کن، یا کارت رو به‌صورت `index.html` ذخیره کن.
- **دکمه‌های کپی، جای‌گذاری و پاک‌سازی،** با پنجره‌ی تأیید قبل از پاک کردن.
- **پیش‌نمایش تمام‌صفحه.**
- **تم تیره و روشن** که انتخابت یادش می‌مونه.
- **ذخیره‌ی خودکار:** کد توی مرورگر (`localStorage`) نگه داشته می‌شه، پس با رفرش چیزی از دست نمی‌ره.
- **پیش‌نمایش امن:** کد کاربر داخل یه `iframe` ایزوله (sandbox) اجرا می‌شه و به ادیتور و حافظه‌ی اون دسترسی نداره.
- **محافظت در برابر حلقه‌ی بی‌نهایت:** اگه اجرای کد تموم نشه (مثلاً `while(true){}`)، دفعه‌ی بعد که صفحه باز می‌شه خودکار اجرا نمی‌شه تا بتونی کد رو درست کنی.
- **مناسب موبایل:** تب‌های «کد» و «پیش‌نمایش»، و رابط راست‌به‌چپ.

### اجرا روی سیستم خودت

نیازی به build نیست. فقط یه فایل ایستاده:

</div>

```bash
git clone https://github.com/miladmohammadimoghadam-coder/Runnercode.git
cd Runnercode
# open index.html in your browser
```

<div dir="rtl">

کتابخونه‌های ادیتور از CDN لود می‌شن، پس به اینترنت نیاز داری.

### ساخته‌شده با

- [CodeMirror 5](https://codemirror.net/5/) برای ادیتور
- [HTMLHint](https://htmlhint.com/) و [JSHint](https://jshint.com/) برای تشخیص خطا
- HTML و CSS و JavaScript ساده، بدون فریم‌ورک و بدون ابزار build

### مشارکت و حمایت

Issue و Pull Request خوش‌آمده. برای تغییرهای بزرگ‌تر لطفاً اول یه Issue باز کن.
اگه Runnercode به دردت خورد، با دکمه‌ی **حمایت از ما** توی سایت می‌تونی از پروژه حمایت کنی.

</div>

---

<a id="english"></a>

## English

**Free online editor to write, run and preview HTML, CSS and JavaScript, in one page, with no install and no account.**

### What is it?

Runnercode is a lightweight Persian-first alternative to CodePen and JSFiddle. Write your code on one side, see the result live on the other. Everything runs in your browser; nothing is uploaded to a server.

### Features

- **Live preview**: the result updates automatically as you type (debounced).
- **Single-file workflow**: write HTML, CSS and JavaScript together in one `index.html`.
- **Error detection**: unclosed tags, duplicate `id`s, JavaScript syntax errors and unbalanced CSS braces are marked right in the editor, with a status bar showing the first problem.
- **Upload / Download**: open an existing `.html`, `.htm` or `.txt` file, or save your work as `index.html`.
- **Copy / Paste / Clear** buttons, with a confirmation dialog before clearing.
- **Fullscreen preview.**
- **Dark and light theme**, remembered between visits.
- **Autosave**: your code is kept in the browser (`localStorage`), so a refresh never loses your work.
- **Safe preview**: user code runs inside a sandboxed `iframe`, isolated from the editor and its storage.
- **Infinite-loop protection**: if a run never finishes (for example `while(true){}`), the next page load won't auto-run it, so you can fix the code.
- **Mobile friendly**: tabbed code/preview layout, RTL interface.

### Run locally

No build step is needed. It's a single static file:

```bash
git clone https://github.com/miladmohammadimoghadam-coder/Runnercode.git
cd Runnercode
# open index.html in your browser
```

The editor libraries load from a CDN, so an internet connection is required.

### Built with

- [CodeMirror 5](https://codemirror.net/5/) for the editor
- [HTMLHint](https://htmlhint.com/) and [JSHint](https://jshint.com/) for error detection
- Plain HTML, CSS and JavaScript. No framework, no build tools.

### Contributing & support

Issues and pull requests are welcome. For larger changes, please open an issue first.
If Runnercode is useful to you, you can support the project via the **Support us** button on the site.
