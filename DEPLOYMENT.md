# 🚀 تعليمات النشر السريع على Netlify

## الطريقة الأولى: النشر من GitHub (مُوصى بها)

### 1. ادفع الكود إلى GitHub
```bash
git add .
git commit -m "Ready for Netlify deployment"
git push origin main
```

### 2. اربط المشروع بـ Netlify
1. اذهب إلى: https://app.netlify.com/teams/omar-tnzxo/projects
2. اضغط "New site from Git"
3. اختر GitHub
4. حدد مستودع `omar-portfolio`
5. تأكد من الإعدادات:
   - **Build command:** `npm run build`
   - **Publish directory:** `dist`
6. اضغط "Deploy site"

## الطريقة الثانية: النشر المباشر

### 1. ابن المشروع
```bash
npm install
npm run build
```

### 2. ارفع مجلد dist
1. اذهب إلى: https://app.netlify.com/teams/omar-tnzxo/projects
2. اسحب مجلد `dist` إلى منطقة النشر
3. انتظر حتى يكتمل النشر

## ⚙️ إعدادات إضافية

### إعداد النطاق المخصص
1. في لوحة تحكم Netlify، اذهب إلى "Domain settings"
2. اضغط "Add custom domain"
3. أدخل النطاق المطلوب
4. اتبع تعليمات DNS

### إعداد المتغيرات البيئية
إذا كان لديك متغيرات بيئية:
1. اذهب إلى "Site settings" > "Environment variables"
2. أضف المتغيرات المطلوبة

## 🔍 اختبار الموقع
بعد النشر، تأكد من:
- ✅ تحميل الصفحة الرئيسية
- ✅ عمل الروابط الداخلية
- ✅ عرض الصور والرسوم المتحركة
- ✅ عمل نموذج الاتصال
- ✅ التجاوب مع الأجهزة المحمولة

## 📞 الدعم
إذا واجهت أي مشاكل:
- تحقق من سجلات البناء في Netlify
- تأكد من أن جميع التبعيات مثبتة
- تحقق من إعدادات `netlify.toml`

---
**ملاحظة:** الموقع سيكون متاحاً على رابط Netlify الافتراضي مثل: `https://your-site-name.netlify.app` 