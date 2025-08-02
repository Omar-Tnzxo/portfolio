<a name="readme-top"></a>

# Omar Hassan - Portfolio Website

موقع شخصي احترافي لعمر حسن - متخصص التسويق الرقمي ونمو الأعمال

## 🚀 النشر على Netlify

### الطريقة الأولى: النشر المباشر من GitHub

1. **ادفع الكود إلى GitHub:**
   ```bash
   git add .
   git commit -m "Ready for Netlify deployment"
   git push origin main
   ```

2. **اذهب إلى Netlify:**
   - افتح [https://app.netlify.com/teams/omar-tnzxo/projects](https://app.netlify.com/teams/omar-tnzxo/projects)
   - اضغط على "New site from Git"
   - اختر GitHub وحدد المستودع `omar-portfolio`

3. **إعدادات البناء:**
   - **Build command:** `npm run build`
   - **Publish directory:** `dist`
   - **Node version:** `18`

4. **اضغط "Deploy site"**

### الطريقة الثانية: النشر من الملفات المحلية

1. **ابن المشروع:**
   ```bash
   npm install
   npm run build
   ```

2. **اسحب مجلد `dist` إلى Netlify:**
   - اذهب إلى [https://app.netlify.com/teams/omar-tnzxo/projects](https://app.netlify.com/teams/omar-tnzxo/projects)
   - اسحب مجلد `dist` إلى منطقة النشر

## 🛠️ التطوير المحلي

```bash
# تثبيت التبعيات
npm install

# تشغيل خادم التطوير
npm run dev

# بناء المشروع للإنتاج
npm run build

# معاينة البناء
npm run preview
```

## 📁 بنية المشروع

```
omar-website/
├── src/
│   ├── components/          # مكونات React
│   │   ├── BusinessCard.tsx # البطاقة الرقمية الجديدة
│   │   └── ...
│   ├── assets/             # الصور والملفات الثابتة
│   ├── constants/          # الثوابت والإعدادات
│   └── utils/              # الأدوات المساعدة
├── public/                 # الملفات العامة
├── netlify.toml           # إعدادات Netlify
└── package.json           # تبعيات المشروع
```

## 🎨 المميزات

### 🌟 المميزات الأساسية
- ✅ تصميم متجاوب (Responsive Design)
- ✅ رسوم متحركة ثلاثية الأبعاد (Three.js)
- ✅ تأثيرات بصرية متقدمة (GSAP)
- ✅ تحسين الأداء (Performance Optimization)
- ✅ SEO محسن
- ✅ دعم متعدد اللغات (عربي/إنجليزي)

### 🆕 المميزات الجديدة
- ✅ **بطاقة عمل رقمية** - رابط `/avenue-omar`
- ✅ تصميم زجاجي حديث (Glassmorphism)
- ✅ خلفية متحركة مع تأثيرات blob
- ✅ أزرار تفاعلية متقدمة
- ✅ تأثيرات hover محسنة
- ✅ انيميشن دخول متدرج

## 🔧 التقنيات المستخدمة

- **Frontend:** React 18, TypeScript, Vite
- **Styling:** Tailwind CSS, Framer Motion
- **3D Graphics:** Three.js, React Three Fiber
- **Animations:** GSAP, Framer Motion
- **Icons:** Lucide React
- **Deployment:** Netlify

## 📱 الصفحات المتاحة

### 🏠 الصفحة الرئيسية
- **الرابط:** `/`
- **المحتوى:** Portfolio كامل مع جميع الأقسام
- **المميزات:** انيميشن دخول، تصميم متجاوب

### 💼 البطاقة الرقمية
- **الرابط:** `/avenue-omar`
- **المحتوى:** بطاقة عمل رقمية احترافية
- **المميزات:** تصميم زجاجي، أزرار تفاعلية، وسائل التواصل

## 📞 التواصل

- **Email:** omar-agha@engineer.com
- **LinkedIn:** [linkedin.com/in/omar-hassan-marketing](https://linkedin.com/in/omar-hassan-marketing)
- **Phone:** +201029752972
- **Business Card:** `/avenue-omar`

## 📄 الترخيص

MIT License - انظر ملف [LICENSE.md](LICENSE.md) للتفاصيل.

---

**تم التطوير بواسطة عمر حسن** 🚀
