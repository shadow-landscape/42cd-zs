# موقع راية القانون - نسخة جاهزة لـ Cloudflare Pages

موقع ثابت 100% (Static HTML/CSS/JS) جاهز للنشر المجاني على Cloudflare Pages.

## 1. تفعيل نموذج التواصل (خطوة واحدة فقط - 30 ثانية)

1. اذهب إلى: https://web3forms.com
2. أدخل بريدك: `rayah.alganunn@gmail.com`
3. اضغط **Create Access Key**
4. انسخ الـ Access Key الذي يظهر لك
5. افتح الملف:
   ```
   contact/contact-form.html
   ```
6. استبدل هذه الكلمة:
   ```
   YOUR_WEB3FORMS_ACCESS_KEY
   ```
   بمفتاحك الحقيقي (مرتين: مرة في النسخة العربية ومرة في الإنجليزية).

بعدها النموذج يعمل مباشرة ويرسل كل الطلبات إلى بريدك.

---

## 2. رفع الموقع على GitHub + Cloudflare Pages (مجاني)

### أ) إنشاء مستودع على GitHub
1. ادخل إلى https://github.com/new
2. اسم المستودع مثلاً: `rayat-alqanoon`
3. اختر Public
4. اضغط Create repository

### ب) رفع الملفات
من جهازك (أو من GitHub Desktop / VS Code):
```bash
git init
git add .
git commit -m "موقع راية القانون جاهز"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/rayat-alqanoon.git
git push -u origin main
```

أو ببساطة اسحب كل محتويات المجلد وارفعها عبر واجهة GitHub (Upload files).

### ج) ربط Cloudflare Pages
1. ادخل إلى https://dash.cloudflare.com
2. من القائمة الجانبية اختر **Workers & Pages** → **Create** → **Pages** → **Connect to Git**
3. اختر مستودع `rayat-alqanoon`
4. إعدادات البناء:
   - Framework preset: **None**
   - Build command: (اتركه فارغ)
   - Build output directory: `/`  (أو اتركه فارغ)
5. اضغط **Save and Deploy**

بعد دقيقة أو دقيقتين سيظهر رابط مثل:
`https://rayat-alqanoon.pages.dev`

---

## ملاحظات مهمة
- لا يوجد أي كود سيرفر أو وظائف مدفوعة.
- النموذج يعمل عبر Web3Forms (مجاني تماماً).
- كل الصور والمسارات نسبية وتعمل على Cloudflare.
- إذا غيرت الـ Access Key لاحقاً، عدّل فقط ملف `contact/contact-form.html`.

تم.
