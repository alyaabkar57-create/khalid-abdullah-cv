# خالد عبدالله — سيرة ذاتية مهنية (نموذج تجريبي)
# Khalid Abdullah — Professional CV (Sample)

سيرة ذاتية احترافية ثنائية اللغة (العربية + الإنجليزية) لمتخصص إدارة أعمال وتسويق.
**جميع البيانات الواردة تجريبية وهمية للأغراض التوضيحية فقط.**

A bilingual (Arabic + English), ATS-friendly one-page CV template for a Business Administration & Marketing specialist. **All data is fictional sample data.**

## الملفات / Files

- `index.html` — النسخة القابلة للتعديل مباشرة من المتصفح (حفظ تلقائي في المتصفح، تبديل اللغة، زر تصدير PDF).
- `Khalid_Abdullah_CV.pdf` — نسخة PDF جاهزة من القالب (صفحتان A4).

## التعديل / Editing

افتح `index.html` في المتصفح، انقر على أي نص لتعديله، ثم استخدم زر **«تصدير PDF / طباعة»** واختر *Save as PDF*.

Open `index.html` in a browser, click any text to edit it, then use **Export PDF / Print** and choose *Save as PDF*.

## النشر / Deployment

- GitHub: https://github.com/alyaabkar57-create/khalid-abdullah-cv
- Cloudflare Pages: https://khalid-abdullah-cv.pages.dev

لإعادة النشر بعد تعديل `index.html`، انسخ الملفات إلى `dist/` ثم شغّل:

To redeploy after editing `index.html`, copy files into `dist/` then run:

```bash
npx wrangler pages deploy dist --project-name khalid-abdullah-cv --branch main
```

موقع ثابت (Static site) لا يتطلب أي بناء (no build step).
