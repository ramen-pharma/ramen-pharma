# Ramen Pharma — Company Website

صفحة تعريفية بشركة Ramen Pharma ومنتج Ramspark Cream.

## رفع الموقع على GitHub Pages

1. أنشئ مستودع (repository) جديد على GitHub، مثلاً باسم `ramen-pharma`.
2. ارفع كل الملفات الموجودة في هذا المجلد (`index.html` ومجلد `assets`) إلى المستودع.
3. من إعدادات المستودع Settings → Pages، اختر Branch: main والمجلد `/ (root)`.
4. بعد دقيقة أو اثنتين، سيكون الموقع متاحاً على رابط مثل:
   `https://<username>.github.io/ramen-pharma/`

## إضافة الفيديو التعريفي (حوالي دقيقتين)

1. ضع ملف الفيديو داخل مجلد `assets` باسم `intro.mp4` (وأضف صورة غلاف اختيارية `video-poster.jpg`).
2. افتح `index.html`، ابحث عن قسم `<section class="video-section" id="video">`.
3. استبدل محتوى `<div class="video-shell">...</div>` بالتالي:

```html
<video controls poster="assets/video-poster.jpg" style="width:100%;border-radius:20px;">
  <source src="assets/intro.mp4" type="video/mp4">
</video>
```

## ملاحظات / أشياء يمكن إضافتها لاحقاً
- بريد إلكتروني رسمي للتواصل
- عنوان الشركة أو الفروع وساعات العمل
- سعر المنتج
- رابط إنستجرام (متوفر حالياً فيسبوك وتيك توك فقط)
