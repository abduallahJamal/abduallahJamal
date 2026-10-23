# دليل ضبط البروفايل — GitHub

الملف ده فيه القيم الجاهزة للنسخ واللصق، والخطوات اللي محتاجة تتعمل من إعدادات الحساب بنفسك
(التوكن المتاح هنا صلاحياته محدودة على المحتوى، فمش قادر يعدّل بيانات الحساب أو إعدادات المستودع).

---

## 1) الصورة الشخصية (Avatar)

- الملف: `assets/avatar.png` (مربّع 800×800)
- الخطوات: GitHub → **Settings → Public profile → Profile picture → Edit → Upload a photo**
  (أو من صفحة البروفايل نفسها: زر الصورة → Edit)

## 2) البانر (Profile banner)

- الملف: `assets/banner.png` (1280×640)
- الخطوات: افتح البروفايل → زر **Edit profile** (أو Settings → Public profile) → **Banner → Upload** → اختر الملف.
- ملاحظة: البانر بيظهر بشكل أحسن لو الصورة عريضة ومش فيها نص قريب من الحواف.

## 3) بيانات الحساب (انسخ والصق)

| الحقل | القيمة المقترحة |
|---|---|
| **Name** | `Abduallah Jamal` |
| **Bio** | `Full-Stack Developer · Python & Django · I build clean, practical web apps` |
| **Location** | `Cairo, Egypt` |
| **Website** | (سيبه فاضي لحد ما يكون عندك بورتفوليو) |
| **Social links** | LinkedIn / X — ضيفهم أول ما تجهزهم |

نسخة بديلة أقصر للـ Bio (لو الحالي طويل):
`Full-Stack Developer · Python · Django · Cairo, EG`

## 4) إعدادات المستودع (Repository)

- **Description:** `My GitHub profile — full-stack developer (Python · Django)`
- **Topics:** `profile` · `readme` · `python` · `django` · `fullstack` · `portfolio`
- **Website:** سيبه فاضي حالياً.
- الطريقة: صفحة المستودع → ⚙️ **Settings** (جنب About) → اكتب الوصف والمواضيع → Save.
- لو حابب تخلي repo خاص بالبروفايل بس: Settings → Danger Zone → **Change visibility**.

### ⚠️ نقطة مهمة: اسم المستودع

GitHub بيعرض README على صفحة البروفايل **بس** لو اسم المستودع مطابق لاسم المستخدم بالحرف.
اسم المستخدم عندك `abduallahJamal`، والمستودع اسمه `Abduallah` — يعني الـ README مش هيظهر على البروفايل تلقائياً.

عندك حلّين:

1. **تغيير اسم المستودع** (الأسهل): Settings → **Rename** → `abduallahJamal`
   (GitHub بيعمل redirect للينكات القديمة). بعدها الـ README هيظهر فوراً على البروفايل.
2. **سيب المستودع زي ما هو** واستخدمه كـ "Profile repo" في مكان تاني، أو انسخ المحتوى في repo جديد اسمه `abduallahJamal`.

## 5) بعد إضافة مشاريع

في `README.md` فيه قسم **Featured Projects** فيه كروت جاهزة (`Project One` / `Project Two`).
لمّا تضيف مشاريع حقيقية، بدّل:
- العنوان باسم المشروع
- الوصف بسطرين: المشكلة → الحل → أهم ميزة
- شارات التقنيات
- اللينك `https://github.com/abduallahJamal?tab=repositories` بلينك المستودع نفسه

## 6) روابط التواصل

في آخر `README.md` فيه بلوك **Let's Connect** — فيه سطور معلّقة (LinkedIn / Email).
شيل التعليق `<!-- -->` وحدّث اللينكات لما تجهز.

---

## ✅ Checklist

- [ ] رفع `assets/avatar.png` كصورة شخصية
- [ ] رفع `assets/banner.png` كبانر للبروفايل
- [ ] تحديث Name / Bio / Location
- [ ] إعادة تسمية المستودع إلى `abduallahJamal`
- [ ] إضافة Description + Topics للمستودع
- [ ] إضافة مشروعين حقيقيين في Featured Projects
- [ ] إضافة LinkedIn / Email في قسم التواصل
