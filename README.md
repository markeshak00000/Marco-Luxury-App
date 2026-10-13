# ماركو للأثاث الراقي - Marco Luxury Furniture

> نظام إدارة متكامل لمصنع ومحل الأثاث الراقي
> تصميم فاخر داكن بالذهبي - يعمل كـ PWA و APK أندرويد

## ✨ المميزات
- 📊 لوحة تحكم شاملة (مبيعات، مخزون، ورشة)
- 👷 إدارة الموظفين
- 👥 إدارة العملاء
- 🛋️ كتالوج المنتجات
- 💰 المبيعات والفواتير + تصدير PDF
- 📦 المخزون وحركة الخامات
- 🔨 إدارة الورشة (حالات: جديد، قيد التنفيذ، مكتمل، تم التسليم)
- 🚚 الموردين والمشتريات
- 💸 المصروفات
- 📈 التقارير + تصدير PDF
- 💾 نسخ احتياطي JSON (تصدير/استيراد)
- ⚙️ الإعدادات والدعم الفني

## 📁 هيكل المشروع
```
marco-luxury-app/
├── www/
│   ├── index.html (التطبيق الكامل)
│   ├── manifest.json
│   └── icon.png
├── capacitor.config.json
├── package.json
├── .github/workflows/build-apk.yml
└── README.md
```

## 🚀 التشغيل كـ PWA (GitHub Pages)
1. أنشئ مستودع جديد باسم `Marco-Luxury-App`
2. ارفع كل الملفات (محتوى www في الجذر أو في مجلد www)
3. من Settings > Pages > فعل GitHub Pages على Branch: main
4. افتح الرابط وسيعمل كـ PWA قابل للتثبيت

## 📱 بناء APK أندرويد
### الطريقة التلقائية (GitHub Actions):
1. ارفع المشروع على GitHub
2. اذهب إلى تبويب Actions > شغل Build Marco APK
3. بعد انتهاء البناء، حمّل ملف APK من Artifacts

### الطريقة اليدوية (محلياً):
```bash
npm install
npx cap add android
npx cap copy
npx cap sync
npx cap open android
# ثم من Android Studio: Build > Build APK
```

## 🎨 الهوية
- الخلفية: #0A0A0F (أسود فاخر)
- الذهبي: #D4AF37
- الخط: Cairo
- اتجاه: RTL عربي

## 📞 الدعم الفني
- واتساب المبيعات: 01227311665
- الدعم الفني: 01277482080
- المطور: ENG.Mark Eshak | Infinity MEN2

## 📄 الترخيص
خاص بمؤسسة ماركو للأثاث الراقي
