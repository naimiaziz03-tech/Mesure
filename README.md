# تنصيب تطبيق فيشة المحول (TAZA II)

الملفات (ضعها كلها في نفس المجلد):
- index.html — التطبيق
- manifest.json — بيانات التنصيب
- sw.js — للعمل بدون انترنت
- template.docx — قالب Word مأخوذ من الملف الأصلي (احتفظ به؛ التطبيق يحمل نسخة منه داخله)
- icon-v2-192.png و icon-v2-512.png و icon-v2-maskable-512.png — الأيقونات

## النشر على GitHub Pages
1. أنشئ مستودعاً (Repository) جديداً على GitHub.
2. ارفع الملفات (ما عدا README وtemplate.docx اختيارياً) في الجذر (root) مباشرة، دون مجلد داخلي.
3. Settings ← Pages ← Source: Deploy from a branch ← Branch: main و/ (root) ← Save.
4. بعد دقيقة افتح: https://USERNAME.github.io/REPO/

## التنصيب على الهاتف
- Android / Chrome: القائمة ⋮ ← «تثبيت التطبيق» (أو زر «تنصيب التطبيق» داخل البرنامج).
- iPhone / Safari: زر المشاركة ← «إضافة إلى الشاشة الرئيسية».

## ملاحظات
- البيانات المحفوظة تبقى داخل متصفح الجهاز، ولا تنتقل بين الأجهزة.
- عند تعديل index.html غيّر رقم النسخة في sw.js (v6 ← v7) ليصل التحديث إلى الهاتف.
