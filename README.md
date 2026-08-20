# موقع عبدالرجيم الشيباني — كهربائي معتمد

موقع شخصي بصفحة واحدة (One Page) لخدمات التمديد الكهربائي، منظومات الطاقة الشمسية، صيانة الثلاجات والغسالات، وبرمجة الموديمات.

## الملفات
- `index.html` — الموقع كاملاً (لا يحتاج أي إعداد إضافي).
- `robots.txt` — يسمح لمحركات البحث بفهرسة الموقع.
- `sitemap.xml` — خريطة الموقع لمساعدة جوجل على الفهرسة.

## خطوات النشر على GitHub Pages (مجاني)

1. أنشئ مستودع (Repository) جديد على GitHub، مثلاً باسم `my-electrician-site`.
2. ارفع الملفات الثلاثة (`index.html`, `robots.txt`, `sitemap.xml`) إلى المستودع.
3. من إعدادات المستودع: **Settings → Pages**.
4. تحت **Build and deployment**، اختر **Source: Deploy from a branch**، ثم اختر الفرع `main` والمجلد `/root`.
5. احفظ، وانتظر دقيقة أو دقيقتين. سيظهر رابط الموقع بالشكل:
   `https://USERNAME.github.io/my-electrician-site/`

## قبل الرفع — عدّل هذا السطر في `index.html`

ابحث عن هذين السطرين في أعلى الملف واستبدل الرابط برابط موقعك الحقيقي بعد نشره:

```html
<link rel="canonical" href="https://REPLACE-WITH-YOUR-USERNAME.github.io/REPLACE-WITH-REPO-NAME/">
<meta property="og:url" content="https://REPLACE-WITH-YOUR-USERNAME.github.io/REPLACE-WITH-REPO-NAME/">
```

وأيضاً في ملف `sitemap.xml`، استبدل الرابط بنفس الطريقة.

## كيف تجعل جوجل يفهرس الموقع بسرعة

1. اذهب إلى [Google Search Console](https://search.google.com/search-console).
2. أضف موقعك (رابط GitHub Pages) كـ "خاصية" (Property) من نوع "بادئة عنوان URL".
3. تحقق من الملكية عبر الطريقة التي يقترحها جوجل (عادة بإضافة ملف HTML أو وسم meta — يمكن إضافته داخل `<head>` في `index.html`).
4. بعد التحقق، اذهب إلى قسم **Sitemaps** وأضف الرابط:
   `https://USERNAME.github.io/my-electrician-site/sitemap.xml`
5. استخدم أداة **URL Inspection** والصق رابط موقعك، ثم اضغط **Request Indexing**.

عادة يستغرق ظهور الموقع في نتائج البحث من عدة أيام إلى بضعة أسابيع.

## تعديل معلومات التواصل

أرقام الهاتف وواتساب موجودة في `index.html` بصيغة دولية (`+967...`). للتعديل، ابحث عن `771217897` و`733592873` واستبدلهما برقمك.
