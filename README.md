# Yazzy Barber

موقع حجز محل حلاقة مبني بـ React + Vite + Tailwind، مربوط بقاعدة بيانات Supabase.

## النشر على Vercel من الموبايل (بدون كمبيوتر)

### 1) ارفع المشروع على GitHub
1. افتح github.com وسجّل حساب (لو ما عندك).
2. اضغط "+" ثم "New repository"، سمّه مثلاً `yazzy-barber`، خليه Public، ثم Create.
3. بصفحة الريبو، اضغط "Add file" → "Upload files".
4. ارفع **كل ملفات ومجلدات هذا المشروع بنفس الهيكل** (حافظ على مجلد `src` كما هو).
5. اضغط "Commit changes".

### 2) اربطه بـ Vercel
1. افتح vercel.com وسجّل دخول بحساب GitHub نفسه (زر "Continue with GitHub").
2. اضغط "Add New..." → "Project".
3. اختر الريبو `yazzy-barber` اللي رفعته.
4. Vercel يكتشف تلقائياً إنه مشروع Vite (Framework Preset: Vite) — اترك الإعدادات الافتراضية.
5. اضغط "Deploy".
6. بعد دقيقة أو دقيقتين، يعطيك رابط نهائي مثل `yazzy-barber.vercel.app` — هذا الرابط شغال ودائم.

## ملاحظات
- بيانات الاتصال بـ Supabase موجودة بالفعل داخل `src/App.jsx` (رابط المشروع + anon key)، لا تحتاج أي إعداد إضافي.
- أي تعديل لاحق: عدّل الملف على GitHub مباشرة (زر القلم ✏️ بأي ملف) واحفظ (Commit) — Vercel يعيد النشر تلقائياً خلال دقيقة.
