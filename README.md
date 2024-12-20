# MyBNB - نظام إدارة حجوزات الشقق

نظام شامل لإدارة حجوزات الشقق باللغة العربية، مصمم لمساعدة مديري العقارات في إدارة الحجوزات وتتبع الإيرادات وتحليل أداء الأعمال.

## المميزات الرئيسية

- لوحة تحكم شاملة لعرض المؤشرات الرئيسية
- إدارة الحجوزات مع إمكانية التصفية والبحث
- عرض تقويمي للحجوزات
- تحليلات متقدمة للإيرادات والإشغال
- واجهة مستخدم عربية بالكامل
- تحديثات فورية للبيانات

## التقنيات المستخدمة

- React.js مع TypeScript
- Material-UI للواجهة
- Firebase للبيانات في الوقت الفعلي
- i18next للترجمة

## متطلبات التشغيل

- Node.js (v14 أو أحدث)
- npm (v6 أو أحدث)

## بدء التشغيل

1. تثبيت الاعتمادات:
```bash
npm install
```

2. إعداد Firebase:
- قم بإنشاء مشروع Firebase جديد
- انسخ بيانات التكوين إلى `src/config/firebase.ts`

3. تشغيل المشروع محلياً:
```bash
npm run dev
```

## الهيكل التنظيمي للمشروع

```
src/
  ├── components/     # مكونات واجهة المستخدم
  ├── config/        # ملفات الإعداد
  ├── i18n/          # ملفات الترجمة
  ├── pages/         # صفحات التطبيق
  └── App.tsx        # المكون الرئيسي
```

## المساهمة

نرحب بمساهماتكم! يرجى اتباع الخطوات التالية:

1. انشئ fork للمشروع
2. أنشئ فرع للميزة الجديدة
3. قم بعمل التغييرات
4. أرسل pull request
